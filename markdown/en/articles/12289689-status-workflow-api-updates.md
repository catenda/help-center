# Status Workflow - API Updates

> Introducing API changes of the new Status Workflow feature, where we diffentiate between shared and published status in accordance with ISO 19650. This article is targeting customers and integration partners using the Catenda API.

We are implementing **Status Workflow**, a significant update to how Catenda manages document and model revisions. This change introduces a distinction between working and official revisions that may require adjustments to your integration.

## 1. Executive Summary

Catenda will differentiate between:

- **"Shared"** revisions (working/draft versions)
- **"Published"** revisions (official/approved versions)

**Immediate Action Required If:**

- Your application integrates with Catenda Hub
- You display revision information to users
- You create new revisions through the API
- You use CAD tool plugins

## 2. What's Changing

### 2.1 Revision Types

Previously, all revisions were implicitly considered "official." Now:

- **"Shared"**: Collaborative working revisions with restricted visibility
- **"Published"**: Official revisions for broader distribution

### 2.2 API Response Changes

**Document API** will include new fields for library items:

```
{  "document": {    "revision": {      "extendedVersion": {        "major": 1,        "minor": null  // or 1,2,3 for Shared      },      "version": 5  // Legacy numbering maintained    }  }}
```

**Models API** changes are minimal:

- Adds filtering capability via scope parameter (scope=published or scope=all)
- Does NOT expose revision status or extended numbering
- Enforces permissions inherited from underlying documents

### 2.3 Default Behavior

**Important**: APIs will return **both** "Shared" and "Published" revisions by default where users have access. This maintains backward compatibility but fundamentally changes the nature of returned data.

## 3. Who Is Affected and How

### 3.1 Not Affected

- ✅ Standalone API applications with no Catenda Hub dependency
- ✅ Applications that don't display or manage revisions

### 3.2 Significantly Affected - CAD Tool Plugins

⚠️ **Critical Issues:**

- Cannot determine if creating "Shared" or "Published" revisions
- Cannot display accurate revision status to users
- May show different numbering than Hub (sequential vs. X.Y format)
- Users won't understand revision context without status visibility

**Required Actions for Plugin Developers:**

1. Evaluate if you display revision information
1. Consider adding user guidance about revision types
1. Plan for potential user confusion about numbering discrepancies

### 3.3 Also Affected

⚠️ Applications that:

- Display revision lists to users
- Create new revisions via API
- Depend on all revisions being "official"
- Use Catenda Site integration

## 4. Technical Implementation Guide

### 4.1 Filtering Revisions

Use the new scope parameter to control which revisions are returned:

```
# Documents APIGET /documents?scope=published     # Published onlyGET /documents?scope=shared        # Shared only (requires permission)GET /documents                     # All (default)# Models API  GET /models/revisions?scope=published  # Published onlyGET /models/revisions                  # All (default)
```

### 4.2 Permission Changes

New ACL rights affect your operations:

- **Viewing "Shared" revisions**: Requires specific permission
- **Creating "Published" revisions**: Only possible through Catenda Hub UI
- **API revision creation**: Creates "Shared" revisions by default

### 4.3 What You Cannot Do via API

- ❌ Create "Published" revisions (Hub-only)
- ❌ Access revision status in Models API
- ❌ See extended numbering (X.Y) in Models API
- ❌ Determine model-to-document relationships

## 5. Migration Considerations

**Existing Projects:**

- All current revisions will become "Published" upon migration
- Version numbers become major revision numbers (e.g., v3 → 3)
- No action required for historical data

**New Behavior:**

- New revisions created via API = "Shared" by default
- Publishing requires manual action in Hub

## 6. Critical Decisions for Your Implementation

**Question 1**: Do you need only official revisions?

- **Yes** → Implement `scope=published` filtering
- **No** → Prepare to handle mixed revision types

**Question 2**: Do you display revision information?

- **Yes** → Plan for numbering discrepancy (especially for Models API users)
- **No** → Minimal impact expected

**Question 3**: Do users create revisions through your app?

- **Yes** → Inform users they're creating "Shared" revisions
- **No** → No action needed

## 7. Known Limitations & Workarounds

**For Models API Users:**

- **Limitation**: Cannot access revision status or extended numbering
- **Workaround**: Use filtering to get only desired revision types
- **User Impact**: Potential confusion about revision numbering differences

**For Collection API Users:**

- Currently only "Published" revisions can be added to collections
- This may change based on customer feedback

## 8. Support Resources

**Documentation Updates Available:**

- [Updated API Reference] - Includes new `scope` parameter

## 9. FAQ

**Q: Will my integration break?** A: No breaking changes at the API level, but user experience may change significantly, especially for CAD plugins.

**Q: Why can't I see revision status in Models API?** A: To maintain backward compatibility, the Models API minimally exposes Status Workflow features. Use filtering to control returned revisions.

**Q: How do users know what type of revision they're creating?** A: Via API, all new revisions are "Shared." Users must use Catenda Hub to create "Published" revisions.

**Q: What if we need more time to adapt?** A: Contact us immediately. Status Workflow will be enabled gradually, and we can discuss timeline options for your organization.
