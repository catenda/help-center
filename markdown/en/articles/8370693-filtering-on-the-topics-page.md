# Filtering on the topics page

The filter menu in an topic board can be opened by clicking on the filter button to the left of the search bar in a [topic board](https://support.catenda.com/en/articles/4670271-issues-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

This article contains information about the following topics

## 1. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so: _Filter name in menu_ - `Filter name in URL=Filter option in URL`

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied. _No filter_ - `status-type=all`

### 1.1 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters

### 1.2 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

## 2. **Filtering in the filter menu**

Here the following filters can be found:

The different filters in the filter menu will only show up if there are topics where the item that is filtered for has been configured.

### 2.1 **My topics**

Assigned to me - `assigned-user=\<User GUID>&assigned-team=\<Team GUID>` _Assigned User_ - `assigned-user=\<User GUID>` _My teams_ - `assigned-team=\<Team GUID>` _Requested by me_ - `requester-user=\<Your GUID>` Topics _I follow_ - `followed-by=me` _mentioning me_ - `mentioned=me`

> **Note:** If you share a link with the "Topic I follow" or the "mentioning me" filters active the user opening the link will have their topic board filtered for topic  they follow and topics they have been mentioned in and not topics you follow and topics you are mentioned in. To share topics you have been mentioned in please use [text search](#h_7fc30a16f0)

_Created by me_ - `created-by=\<User GUID>`

### 2.2 **Status / Type**

_All open status_ - `status-type=open` _Specific open status_ - `status-type=\<Status GUID>` _All closed status_ - `status-type=closed` _Specific closed status_ - `status-type=\<Status GUID>` _Type_ - `type=\<Type GUID>`

### 2.3 **Due date**

_Overdue_ - `due=overdue` _All with a due date_ - `due=present` _No due date_ - `due=none`

### 2.4 **Updated**

With the date filter you can select a timeframe for when the topics were last updated. _Updated_ - `updated-from=\<Epoch Unix Timestamp>&updated-to=\<Epoch Unix Timestamp>` Read [this](https://support.catenda.com/en/articles/6511685-date-filter) article to learn how to easily select dates on the page.

### 2.5 **Assigned to / Requested by**

_Assigned to no-one_ - `assigned=unassigned` _No team assigned_ - `assigned-team=unassigned` _Assigned to team_ - `assigned-team=\<Team GUID>` _Not assigned to user_ - `assigned-user=unassigned` _Assigned to user_ - `assigned-user=\<User GUID>` Assigned operator - `assigned-op=and` By default you can only search for the assigned user OR the assigned team. In Catenda Hub you can set an assignee as user@team To find all topics of this type**,** filter by the team and the user, and add &assigned-op=and to the end of the URL.

_Not requested_ - `requester=unassigned` _Not requested by team_ - `requester-team=unassigned` _Not requested by user_ - `requester-user=unassigned` _Requested by user_ - `requester-user=\<User GUID>`

### 2.6 **Created by**

_Created by user_ - `created-by=\<User GUID>`

### 2.7 **Milestone**

_Milestone_ - `milestone=\<Milestone GUID>`

### 2.8 **Custom field**

_Custom field has value_ - `custom-field-has-value-\<Custom field GUID>=true` With the "has value" option in the filter menu all topics with that have a value configured for that custom field can be filtered. Custom field types that can be filtered on has value: Date Decimal Dropdown Integer Text

_Custom field specific value_ - `custom-field-item-\<Custom field GUID>=\<Value GUID>` Custom field types that can be filtered on specific value from the filter menu: Dropdown

Some values in custom fields where values can be configured can be filtered. Filter for values by writing a search phrase in the search or filter bar and select the corresponding custom field. Custom field types that can be filtered by typing in the search or filter bar: Decimal Dropdown Integer Text

_Custom field has no value_ - `custom-field-has-value-\<Custom field GUID>=false` Filter on all topics where a custom fields does not have any value. Custom field types that can be filtered on no value: Date Decimal Dropdown Integer Text

> **Note:** Custom fields that are set as required will always have a value. You will therefore not be able to search for "has value" or "has no value" can therefore not be searched for a custom field that is set as required.

### 2.9 **Label**

_Label_ - `label=\<Label GUID>` Labels in their own label group are shown in a separated list.

### 2.10 **Links**

Linked - `associations=exists` Filter on topics linked to model objects in the 3D viewer.

Unlinked - `associations=does-not-exist` Filter on topics that are not linked to model objects in the 3D viewer.

Linked to selected objects - `link=backlink` If it is not already open, the 3D panel will open up. Select objects from a model in the 3D viewer to filter on topics linked to the selected objects.

## 3. **Filtering in the search or filter bar**

In addition to the filter menu on the left there is some functionality that is only available through the search or filter bar. This is what the search or filter bar can look like when it is highlighted:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Below the search or filter bar a menu with suggested filters opens up. The first filter in the filter menu is suggested after highlighting the search or filter menu. Press enter to apply this filter or use the arrow keys to navigate between the different filters.

### 3.1 **Saved filters**

If you have any saved filters in a topic board those will be the first available filter in the filter menu and will be suggested as soon as the search or filter box is higlighted:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Click on the filter to open filter the board on the saved set of filters that have been given a name. Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about how to save a set of filters.

### 3.2 **Text search**

_Text search -_ `search=\<Search phrase>` After entering characters in the search or filter bar, the first suggested filter changes to the text search.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Content that can be searched on** Topic title Topic description Topic comments

**Capitalization** The text search is not sensitive to upper or lowercase characters.

**Character amounts** Single character Content that includes the searched character is matched unless it is a unicode letter with a value that is 58 or higher at the start of the content.

Two characters Content that has a single word, separated by a separator character like a space, that matches the search phrase is included in the results.

Three or more characters Content that matches the search phrase in any part of the content is included int he results.

**Whitespace** Whitespace characters at the beginning of a search phrase are removed.

**Searching for mentioned members or teams** Topics where a member or team has been mentioned in a comment or description can be found using the text search:

Member or team name Search on the name of the member or team to find all plain text occurrences of that member or team name.

Mentioned member Search on the email of a member to find all plain text occurrences of that members email. This includes where they have been mentioned. Search on `#[\<Email of member>]` to find only the occurrences where that member is mentioned.

Mentioned team Mentioned teams can be searched on by searching the GUID of that team. To find the GUID of a team, go to the [content page of that team](https://support.catenda.com/en/articles/7891755-team-page) by clicking on its name on the [teams tab of the members and teams page](https://support.catenda.com/en/articles/4670291-members-and-teams-page). The URL should look something like: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Search on the team GUID to find all plain text occurrences of that team GUID. This includes where they have been mentioned. Search on `#[\<team GUID>]` to find only the occurrences where that team is mentioned.

### 3.3 **Custom fields - Text**

If a search pharse starts with a unicode character with a unicode value that is 58 or higher the following filters will appear towards the bottom of the list of suggested filters.

_Text custom field -_ `custom-field-\<Custom field GUID>=\<Search phrase>` If a text custom field is enabled in the topic board the content of text custom fields in all topics in the board can be filtered with this filter.

### 3.4 **Number search phrase**

If a search pharse starts with a unicode character with a unicode value that is between 33 and 57 the following filters will appear towards the bottom of the list of suggested filters.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

This includes the following characters: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`\*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Topic -_ `issues=\<issue number>` When a search phrase starts with a number the topic number search appears as a suggestion in the search or filter bar. The suggested filter can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

While it is possible to filter a board for topic numbers with more than just numbers topics can only be found with their number with this filter. If more than just numbers are provided the filter will disappear from the menu but the board will still be filtered on the entered phrase.

Filtering on one or more topics by number It is only possible to search on one topic at a time from the search or filter bar. If the topic with the Catenda topic number 123 exists in the board the url will have `&issues=123` in it when it is filtered on topic number 123. It is possible to enter more topic numbers in the url, for example: `&issues123,124,125` would result in all three topics being displayed if they exist in the board. Filtering on multiple topics like this is only possible by editing the URL.

### 3.5 **Custom fields - Number**

_Integer custom field -_ `custom-field-\<Custom field GUID>=\<Search phrase>` If an integer custom field is enabled in the topic board the content of integer custom fields in all topics in the board can be filtered with this filter.

_Decimal custom field -_ `custom-field-\<Custom field GUID>=\<Search phrase>` If a decimal custom field is enabled in the topic board the content of decimal custom fields in all topics in the board can be filtered with this filter.

### 3.6 **Custom fields - Dropdown**

If a search pharse matches the name of a value in a filter, the filter that matches the best will be suggested in the suggestion box.

_Dropdown custom field_ _-_ `custom-field-item-\<Custom field GUID>=\<Dropdown value GUID>` If the search phrase matches a value in a dropdown custom field with up to 10 values it will be suggested to search on that dropdown value.
