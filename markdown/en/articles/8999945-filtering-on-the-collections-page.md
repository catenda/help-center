# Filtering on the collections page

The search and filter option you will see in the top part of the window. You can search by writing the name of the collection.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/svz5chty/01-intro.png)

In the search bar you can search for any collection you have access to.

## 1. **Filter left panel**

By clicking the filter button a panel will appear on the left side. By checking the boxes of you will narrow down the search. These filters can be saved at the top of the filter list. When you apply any of these filters the filter text will be added to your URL. If you share this URL, the person opening it will see the same filter as you are seeing if they have access to it. For example, if you share a URL with the filter "I follow" enabled the recipient will see filters they follow when they open the URL When you hover over any of the filters in the left panel you can click on only on the right of the filter to remove any other, previously applied, filters.

## 2. **Saved filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about how to save a set of filters

## 3. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so: _Filter name in menu_ - `Filter name in URL=Filter option in URL`

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied. _Collections followed by me and teams I am part of_ - `followers=my-teams,me`

### 3.1 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters

### 3.2 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

### 3.3 **Collections I follow**

_I follow_ - `followers=me` Collections followed by the user.

_My teams follow_ - `followers=my-teams` Collections followed by teams that the user is part of.

_All collections_ - `followers=all` All collections with or without follower. This filter automatically gets applied when The x button in the search bar is clicked or or both the I follow and My teams follow filters are disabled.

### 3.4 **Created by me**

Created by - `createdBy=\<Creator GUID>` There is no user interface button for this filter. When you filter on private or shared with project, this will automatically be set to your own user but you can change it for the GUID of another user.

Private - `visibility=private` Shared with project - `visibility=project-members`

### 3.5 **Finalized**

Finalized - `finalized=true` Not finalized - `finalized=false`

### 3.6 **Externally shared**

Shared externally - `sharedBy=email,link`

> **Note:** By writing either email or link here you can narrow down your search

Not shared externally - `sharedBy=not-shared`

### 3.7 **Date filters**

Published - `publishedAtFrom=\<UTC timestamp>&publishedAtTo=\<UTC timestamp>` Click on select dates to select dates in between which you would like to search Click [here](https://support.catenda.com/en/articles/6511685-date-filter) to learn more about the date filter

## 4. **Text search**

You can search for complete matches of text in file names that are at least 3 characters long

### 4.1 **Text search**

_Text search_ - `search=test`

**Content that can be searched on** collection name

**Capitalization** The text search is not sensitive to upper or lowercase characters.

**Character amounts** Any amount of characters Content that includes the searched phrase is matched.

**Whitespace** Whitespace characters at the beginning of a search phrase are removed.
