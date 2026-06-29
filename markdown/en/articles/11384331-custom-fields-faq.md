# Custom fields FAQ

The limitations of how custom fields can be interacted with will be explained here.

## 1. **Project \<=> Project**

Custom fields have a unique id within a project and can therefore not be exchanged from one project to another. Even if custom fields have the same name in both projects the id will be unique and the field will not be recognized.

## 2. **Topic board \<=> Topic board**

When a custom field is enabled for two topic boards within the same project, topics can be moved between the boards and the field will be maintained.

## 3. **Exporting custom fields on topics**

Custom fields on topics can be exported in the following ways

### 3.1 **Topic PDF export**

Custom field values are displayed in the PDF export of topics

### 3.2 **Topic BCF export**

Custom fields are not yet included in the exported BCF. Custom fields will be part of the BCF 4 standard when it gets released. After release we, and other BCF tools that follow the standard will work on making the field available for exchange.

### 3.3 **​Topic Excel export**

A column will be added for each custom field in the topic board.

### 3.4 **API**

Custom fields in topic boards [can be configured](https://developers.catenda.com/topic-api/update-a-topic-board) via the API. Custom fields on topics [can be configured](https://developers.catenda.com/topic-api/update-topic) via the API. Information about custom fields on topics can be retrieved via the API.

### 3.5 **Report action**

Custom fields on topics are only available for export with the PDF, BCF or excel exports and via the API.

## 4. **Exporting custom fields on documents**

Custom fields on documents can be exported in the following ways

### 4.1 **Report action**

When the on demand reports feature has been requested to be enabled for a project the reports action is made available. If the report is configured with the name of the custom field information about custom fields of documents selected in the documents tabel can be exported to a report and saved in any of the available report formats.

### 4.2 **API**

Custom fields on documents are only available for export with the report action.

### 4.3 **Document download**

Custom fields on documents are only available with the report action. When documents are downloaded with the download action in the documents table the original document is downloaded. Catenda does not alter the document in any way so custom fields are also not added as metadata.
