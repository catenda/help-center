# Filtering on the members and teams page

The search and filter option can be found in the top part of the window. By writing the name of the member or team the rows in the members or teams tables can be narrowed down.

This is what the search or filter menu can look like on the members and teams page:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/sebc204e/01-intro.png)

## 1. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so: _Filter name in menu_ - `Filter name in URL=Filter option in URL`

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied. _No filter_ - `status-type=all`

### 1.1 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters

### 1.2 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

### 1.3 **Tabs**

Members tab - `v=members` Teams tab - `v=teams`

### 1.4 **Role**

Administrator - `aggregatedRole=administrator` Member - `aggregatedRole=member`

### 1.5 **Team**

Team name - `memberOfTeams=<GUID> `

## 2. **Text search**

_Text search -_ `search=<Search phrase>` After entering characters in the search or filter bar, the first suggested filter changes to the text search.

**Content that can be searched on** Member account name Member email address Team name

**Capitalization** The text search is not sensitive to upper or lowercase characters.

**Character amounts** Any amount of characters Content that includes the searched phrase is matched.

**Whitespace** Whitespace characters at the beginning of a search phrase are removed for matches the beginning of the content. Whitespace characters are included for matches in the middle of the content.

## 3. **Sort**

Documents can be sorted by clicking the header of each column. The header can be clicked multiple times to revert or disable the sorting.

_Name, a-z_ - Default _Name, z-a_ - `sort=user-desc` _Role, a-z_ - `sort=aggregatedRole-desc` _Role, z-a_ - `sort=aggregatedRole-asc`
