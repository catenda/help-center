# Filtering on the objects page

The filter panel on the objects page can be opened by clicking on the filter button to the left of the search bar on the objects page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/01-intro.png)
This is what the search or filter menu can look like when opened:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/02-intro.png)

## 1. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so: _Filter name in menu_ - `Filter name in URL=Filter option in URL`

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied.

**No filter**

### 1.1 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters

### 1.2 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

### 1.3 **Models**

Click on 3D to the right of the models category in the filter menu to filter on all models that are currently loaded into the 3D viewer.

Model name - `model=\<Model GUID>` Filter on a set of project models.

### 1.4 **Selected**

Selected - `selected=true` Filter to only display rows for objects that are selected in the 3D viewer.

## 2. **Filters that are not listed in the filter panel**

### 2.1 **Query**

Query search - `query=\<Product>,\<Operator>,\<Value>` Click in the Search or filter bar to configure a filter that compares two values.

**Product** The first selection can be any kind of IFC product. This is what the product dropdown can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/03-query.png)

**Operator** The operator can only be selected after a product has been selected. The operator part of the query filter decides how the product is compared against the value. Depending on if the product can have any value or if the product can only have a limited set of values different operators can be chosen from:

Always available operators: Equals - `equals` When the selected product has exactly the entered value

Does not equal - `not-equals` When the selected product does not have exactly the entered value

Exists - `exists` When exists is selected, only a product can be selected and not a value as all values are part of this filter

Does not exist - `not-exists` When does not exist is selected, only a product can be selected and not a value as all values are part of this filter

Limited set of value operators This is what the operator dropdown can look like when the selected property has a limited set of values:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/04-query.png)

Contains - `contains`

Does not contain - `not-contains` To get results about products that do not contain a specific value

Has value - `has-value` When has value is selected, only a product can be selected and not a value as all values are part of this filter

Any value operators This is what the operator dropdown can look like when the selected property can have any value:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/05-query.png)

In Range - `range-inclusive` When the in range operator is selected there are two value fields. This is what it can look like when an in range filter is edited.:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/06-query.png)

The range will be anything from the first value to the second value.

Greater Than or Equals - `greater-than-equals`

Greater Than - `greater-than`

Less Than or Equals - `less-than-equals`

Less than - `less-than`

**Value** The value field behaves differently depending on the possible values that the selected product can have.

Number value When the selected product can only have a number value arrows are displayed when the value field is clicked and only numbers can be entered.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/07-query.png)

Suggested values When a product can have a text value it can be written directly in the value field. This is what the value menu can look like when the Entity product has been selected.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/08-query.png)

When clicking in the value field a list of suggested elements is displayed below the field. If the selected product can only have a limited set of values, this limited set of values is displayed in the suggested elements list. If the selected product can have any value the suggested elements list shows a list of values that other products of this kind have.
