# Copy link action

With the copy link action a link that displayes only the selected table rows can be copied.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/01-intro.png)

Select one or more rows in a table and click on the copy link icon or open the action menu and click on the copy link action.

## 1. **Copy link in models**

Select models table elements and use the copy link action to copy a link that opens the models table filtered on only those elements.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-036d3ef692a4.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-d473a08316d9.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-93f9ec98b273.png" width="190"/>

In the URL the topic filter will look like:

`https://hub.catenda.com/project/<Project-GUID>/models?items=<Model-GUID>,<Model-GUID>,<Model-GUID>`

_Access required:_ Users opening the link will need read access to the documents that are linked to each model in the copied link.

## 2. **Copy link in topics**

Select elements from any topic board and use the copy link action to copy a link that opens the topics table filtered on only those elements.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-8ff62194b021.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-bfe92aebbad0.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-d5d860aee52d.png" width="190"/>

In the URL the topic filter will look like:

[`https://hub.catenda.com/project/<Project-GUID>/issues?issues=<Topic-number>,<Topic-number>&status-type=all&board=<Topic-board-GUID>,<Topic-board-GUID`](https://hub.catenda.com/project/<Project-GUID>/issues?issues=<Topic-number>,<Topic-number>&status-type=all&board=<Topic-board-GUID>,<Topic-board-GUID)`>`

_Access required:_ Users opening the link will need read access to the topic boards that the linked topics are in.

> **Note:** Links with up to 100 topics can be created.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/02-copy-link-in-topics.png)

## 3. **Copy link in documents**

Select documents table elements and use the copy link action to copy a link that opens the documents table filtered on only those elements.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-3e8ac1581a38.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-adfb4a0cfa24.png" width="190"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/35m8h035/inline-eadb7abae0a4.png" width="190"/>

In the URL the topic filter will look like:

[`https://hub.catenda.com/project/<Project-GUID>/libraries/<Document-library-GUID>/items?items=<Library-item-GUID>,<Library-item-GUID`](https://hub.catenda.com/project/<Project-GUID>/libraries/<Document-library-GUID>/items?items=<Library-item-GUID>,<Library-item-GUID)`>`

_Access required:_ Users opening the link will need read access to the folders/documents

> **Note:** Search or filter to share a link to documents from multiple folders.
