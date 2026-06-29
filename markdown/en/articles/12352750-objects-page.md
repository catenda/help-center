# Objects page

The objects page can be found as a sub page to the models page. A table with information about the project models is displayed. Comparison filters can be combined to extract only the information that is asked for. This page combines elements of the QTO menu in the information panel and property value libraries on the libraries page and will eventually replace both.

![Dashboard Models Bookmarks Objects Storey Configurator](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/01-intro.png)

## 1. **Search or filter**

This is what the search or filter menu can look like on the objects page

![Search or filter Select Plus Models Selected Text search](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/02-search-or-filter.png)

Click [here](https://support.catenda.com/en/articles/12353642-filtering-on-the-objects-page) to read more about filtering on the objects page.

## 2. **Products table**

The products table can look something like this:

![Selected 3D action menu download settings entity column GlobalId column LongName column IfcProject IfcBuildingelementProxy one row is selected in table](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/03-products-table.png)

Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to work with tables in Catenda.

### 2.1 **What is a product?**

The name products comes from the fact that each row is a product of the process that happens when an IFC is imported.

### 2.2 **Displayed information**

As soon as the latest revision of a model has finished processing a row for each product that was recognized in the ifc file can be displayed in the products table. Only information of the latest revisions of the models in a project is displayed.

### 2.3 **Selected item actions**

After selecting an element row selected item actions appear towards the top of the products table. This is what the selected item actions menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/04-selected-item-actions.png)

**Viewer** Click on the 3D icon or use the viewer action to select the selected elements in the objects table in the 3D viewer.

**Isolate** Use the isolate action to isolate the selected elements in the objects table in the 3D viewer.

**Hide others** Use the hide others action to hide all objects in the 3D viewer except the selected objects.

### 2.4 **Row content**

**Access** Only product rows for the latest revisions of models that members have access to are displayed. _Access required -_ Read

**Product row** Product rows cannot be opened as in other tables. Product rows can only be displayed in the 3D viewer through the action menu.

**Selection** Row selection works slightly differently than in other tables around Catenda. Unlike other tables around catenda the selection does not get reset when going to another page and coming back or changing a filter. In the products table the selection is only reset when the page is refreshed. As there will often be thousands of objects selected it is more common that selected rows are not in view. A different filter might be applied making it so the selected rows are no longer displayed in the table but they will remain selected.

### 2.5 **Export**

Click on the download button towards the top of the products table to export it.

![Download button](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/05-export.png)

Rows It is only possible to get all rows of the enabled models. Selecting rows does not limit the rows in the exported files. The only filter that can limit the amount of rows is the models filter. While rows may look limited in the table, the exported file will include all rows for the models that are available.

Columns One column for each column that is enabled in the products table is exported to the file. Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to manage table columns.

**Export objects** Choose to export to Excel or CSV in the export objects menu:

![Export objects Excel CSV](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/06-export.png)

**Preparing export** After clicking on export a menu can be seen that says preparing spreadsheet towards the bottom right.

![Preparing export Preparing spreadsheet](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/07-export.png)

During this time it is safe to continue navigating around Catenda as long as the page is not refreshed. When the spreadsheet becomes available it looks like this and the file will start downloading in the browser:

![Export ready Spreadsheet available](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/08-export.png)

### 2.6 **Columns**

Some columns in the products table are enabled by default while others can be hidden and have to be enabled. This is what the column dropdown in the products table can look like:

![Attributes Type GlobalId Name Tag Project Site Building Refresh](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/09-columns.png)

**Toggle** Enable or disable all columns with this toggle

**Filter** Type the name of a column or column category filter the columns dropdown for that column. It could be that the column that is searched for is in a retracted column category so be sure to expand each category to see if there result could be in that category.

**Reset** Click on the reset button to reset the columns back to the default columns

Based on the configured column order the first columns are displayed while the table might have to be scrolled sideways to show other enabled columns. The default order and visibility setting of the columns on the documents page is as follows:

- Attributes
    - Entity
    - GlobalId
    - LongName
    - Name
    - ObjectType

Furthermore the products table may have any number of columns depending on the amount of properties and property sets that are in each of the models. Each set of columns has a main category with sub categories. The toggle butotn can be used to toggle the whole category on or off. Categories can be expanded and each column in the category can be enabled/disabled individually.

**Column preferences** Unlike other table configurations some typical preferences that can been configured are locked in the products table.

Column preferences are not saved between sessions. Columns cannot be re-ordered, only enabled and disabled. It is not possible to sort the table by a different column by clicking on the cell in the header row of the column. It is not possible to change the sorting direction of the column the table is sorted by. It is not possible to draf the cell in the header row out of the table to disable the row, rows have to be disabled via the column dropdown.
