# Structuring documents

There are several ways structure and name your folders and documents. Depending on your type of project different structures and naming conventions might work better for you than others. This article contains some helpful tips when it comes to deciding how to set up your data environment.

## 1. **Element names**

There are several factors that can influence what items in a structure are named. Discoverability and path length are often important factors.

### 1.1 **Ownership**

The person setting the name is often familiar with the contents of the item being named.

**Personal documents** When naming items for personal use a personal way of naming the item is often the best as the person naming the document will be able to easily find the item by searching on it later. Even the person naming the item can struggel with finding their own information again later.

**Collaboration documents** When naming items for collaboration multiple people will be working with the different items. Names of folders are therefore often pre-defined in projects so they are easy to recognize across the different projects of a certain type that belong to the ame organization.

**Minimum requirements** Minimum requirements for document naming are often agreed upon. Since different words can have different meaning to different people it is often important to discuss what namings are given to items with the team so everyone is aware about what to name items and what to search for.

### 1.2 **Naming schemes**

Following good practices for the naming of documents is always helpful but everyone has their own preferences. A naming strategy that makes sense to you does not always make sense to others.

**Team-wide naming schemes** Within a team, contributors to a file structure often agree upon a naming scheme. This can be a verbal suggestion, like telling people to put the date in the name, or it can be enforced by creating a [naming convention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) according to which people have to name their files to be able to upload at all.

**Project-wide naming schemes** In a common data environment, there are often multiple teams that come together. Teams might not yet have a naming rule in place or be willing to change theirs, but if they have already been naming their documents one way for a very long time it can be hard to convince them to do otherwise. In this case a good solution is to allow people to upload files with their preferred name as long as they change the name of the document that contains the file to the convention agreed upon by the project. This way the team member will be able to find their document by the [original name of the file](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page) while a project member will be able to find it by its [document name](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page).

### 1.3 **Naming length**

Being descriptive and writing out full words can help with this as you can read the word and at a glance understand the contents of the document. What this does not mean is that the document name should be a whole sentence. Document names that are too long to read can look like a wall of text and are quickly glanced over. It is therefore recommended to keep names to 1 to 5 words.

**External limitations** Within Catenda folder structures of any path length can both be imported and exported. Other sofware that this information is exchanged with might have limitations to the total amount of characters of the parent folders and the document name that form the path to a document within the structure. Zip files are often used to exchange folder structures. In Windows the path limit for zip files is 260 characters for example. In OneDrive and SharePoint this limit is increased, but still limited to, 400 Unicode units.

### 1.4 **Version control**

A typical situation people will end up with is that they call their document something like:

**Presentation\_Final** Then when they need to make a change it becomes: _Presentation\_Final\_Final, Final\_Final\_For real, Final\_LastOneIPromise._ At which point you give up and just call the next one: _Presentation\_Submitted_ This situation can be prevented by deciding a versioning convention from the beginning. You could start your file with _Presentation\_v1_, _Presentation\_v2_, etc... This will make sure different versions of the same file in a logical order. While there is a good revision system on Catenda it can still make sense to add a version number. Sometimes your local revision count differs from the one that was uploaded. Say that you uploaded v3 of the presentation but then the next one you uploaded was v5. The revision on Catenda will increment by one while your local revision has incremented by 2. This way you can keep track of which version is the right one.

### 1.5 **Separating information**

Historically systems have struggled with spaces in document names. While many systems are able to handle spaces in document names nowadays there might still be reasons to remove spaces from document names You might want to be able to search for a two words together that are not two separate words. You could also hope to compress the amount of characters in a name by removing the spaces. When you take a normal filename like:

**this is a normal file name that is very long with many words.png** and you remove the spaces it becomes an unreadable garbled mess as you need some visual ques to where the word boundaries lie:

**thisisanormalfilenamethatisverylongwithmanywords.png** If compression is your coal you do not want to introduce another character to separate each word because you would be back to the same length as before. Instead what you can do is capitalize each word.

**ThisIsANormalFileNameThatIsVeryLongWithManyWords.png** While this is already slightly better it is still pretty hard to read with longer names. If the goal is to minimize space you can attempt to group words that belong together:

**ThisIs\_ANormalFileName\_ThatIs\_VeryLong\_WithManyWords.png** Now we are beginning to enter the territory of a good, short file name that is readable. Even when file length does not make sense, thinking about compressing words like this makes sense as it is easier to understand grouped words at a glance. If you do not care about how long your filename gets what you can to make it even better is by introducing a secondary separator. See here how grouped words are separated in one way while the words within each group are separated in another way.

**This-is\_A-normal-File-name\_That-is\_Very-long\_With-many-words.png** Note that by separating each word it was possible to add capitalize each first word but then have lowercase for the next ones.

### 1.6 **Compressing information**

In cases where there are many different documents that are all slightly different it does not make sense to repeat the same 4 words over and over again just to add a variation on the 5th word. In this case you might want to use an abbreviation for each word. Example: _Architecture_ can turn into _ARC_, First floor can turn into 1st. The fact that you can have more information in less space is both a strength and a weakness. While it is easy to be 100% correct with the file name information this way, this is not always the best way to name your files. When adding abbreviations you quickly start to notice your files names turn into a garbled  unreadable mess. Take for example: _20110101\_ARC\_BLDG1\_BLCK2\_FLR4\_Q4\_Wa3\_Win4\_S\_C\_v4_ While it might make sense to the file author that this was a file from: Jan. 01 2011 about the fourth version of a concrete sill in window 4 on wall 3 on floor 4 on block 2 in building 1 by the architect. I am pretty sure no-one else in the project will take the time to read it. Especially not when what the searcher was really looking for was:

**20110101\_ARC\_BLDG1\_BLCK1\_FLR4\_Q4\_Wa2\_Win3\_S\_C\_V4** Which is a completely different window sill! If it comes to this level it is better to split your files up in folders.

### 1.7 **Sorting order**

The document section is automatically sorted by name. It can therefore be a good idea to add some characters to the beginning of the document so the most relevant document comes first.

**Chronological order** In order to get a historical overview on Catenda Hub you can always sort by published or created. By standard the documents are sorted by name. When a member opens up a folder for the first time, the most recent document might therefore not be at the top. To combat this you can add the date of the document to the front of the document: _20110101_ would be the first of January 2011. This can also be helpful if you have documents that were created a long time ago and then imported to Catenda Hub. Although this name can be altered it can be a useful bit of information when you are looking for a document. This way you can also sort the name column by date.

**Alphanumerical order** To find out what characters come before other characters please refer to the [sorting order of lists](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) on Catenda. In order to get your documents in order of importance you can always sort by labels or amount of revisions. By standard the documents are sorted by name. When a member opens up a folder for the first time, the most important document might therefore not be at the top. To combat this you can add a character to the beginning of the name that makes it so it comes first. For example you can call your files: _1.0 Most important. 1.1 Less important, 1.2 etc..._ Then you might find out that some breaks your rule by accidentally uploading a document with a 0 in front which ends up coming first. What you might then do is add an \_ in front of the name to make sure it comes before any item. This battle of who is first can seem endless. It can therefore help to look at the [sorting order of lists](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) to see what characters come before others to see what makes sense to use in your case.

## 2. **Subfolders**

It can be hard to find information if there is a lot of information in a list and you have to scroll far down to find the information you are looking for.

### 2.1 **When to move documents into folders**

If there are too many documents or folders in a folder, they can become hard to find as you will have to scroll far down the list to find the document you are looking for. At this point it often makes sense to add a sub folder in this list and divide the documents by their most important property.

This can be a range of properties like:

**Type of document (Drawing, image, spreadsheet)**

**Related topic (Walls and windows)**

**Field of study (ARC, MEP, STR)**

**Party that uploaded it (Group 1, Group 2, Group 3)**

**Date of upload (20110101, 20231225)**

**Maturity (Draft, Submitted, Approved, Denied)**

Reasons that can influence the decision of how to divide your documents can be:

**Discoverability**

**Access control**

### 2.2 **When to move documents out of folders**

After working with a document structure for a bit you will notice that you start to create many sub-folders. If it takes many clicks to get down to the subfolder you did not solve the problem you were trying to solve by making sub folders in the first place because the information is still hard to find. It is recommended to not go further down than 3 layers when making sub folders. This is because most people might remember the last two folders they were in but the deeper you go the more you start to forget where you came from. In order to prevent this you can move your sub-folders up a level.

**Here is an example of a folder that is 4 levels deep:** 01\_Models-and-drawings 0101\_Models 010101\_ARC 01010101\_Window 01010102\_Wall 010102\_MEP 01010201\_Ducts 01010202\_Vents 010103\_STR 0102\_Drawings

**This folder can be simplified to become:** 0101\_Models\_ARC 010101\_Window 010102\_Wall 0102\_Models\_MEP 010201\_Ducts 010202\_Vents 0103\_Models\_\_STR 0201\_Drawings

**Or maybe even simpler:** 010101\_Models\_ARC\_Window 010102\_Models\_ARC\_Wall 010201\_Models\_MEP\_Ducts 010202\_Models\_MEP\_Vents 010301\_Models\_\_STR 020101\_Drawings

As you can see, adding multiple folders that are similar on the same level can help reduce the amount of clicks it takes to get down to the folder containing the documents you are looking for. Another thing you might notice is that the more you simply the folder structure, the longer the file names become. When filenames become too long they become hard to read. It is therefore important to keep a balance between [file name length](#h_7549bd95d9) and [folder depth](#h_e27bb794b2).

## 3. **Folder structure**

### 3.1 **Type of document**

In this document structure you structure your files after what type of document it is. All floorplans go in the floorplans folder, all meeting summaries go in the summaries folder etc. This file structure is easier to use for the client as files that are delivered by consultants are all gathered in once place. This file structure is harder to use for the consultants as they have many different places where they deliver their files.

**Example of file structure** An example of this type of document structure can be:

0101\_Information 010101\_Admin 010102\_Contracts 0201\_Images\_Presentations YYMMDD\_Presentation-title.ppt 0202\_Images\_Site-visits YYMMDD\_Site-visit-title.jpg 0301\_2D 03010101\_Plan\_Floor 030101010101\_DWG\_ARC YYMMDD\_Drawing-title.dwg 030101010102\_DWG\_STR 030101010103\_DWG\_MEP 030101010103\_DWG\_LAN 030101010201\_PDF\_ARK YYMMDD\_Drawing-title.pdf 030101010202\_PDF\_STR 030101010203\_PDF\_MEP 030101010203\_PDF\_LAN 03010102\_Plan\_Ceiling 03010103\_Plan\_Fire-escape 03010201\_Section 03010301\_Elevation 0302\_3D 03020101\_Models\_Archicad 030201010101\_PLN\_ARC 030201010102\_PLN\_STR YYMMDD\_Drawing-title.ifc 030201010103\_PLN\_MEP 030201010104\_PLN\_LAN 030201010201\_IFC\_ARC 030201010202\_IFC\_STR 030201010203\_IFC\_MEP 030201010204\_IFC\_LAN 03020102\_Models\_Navisworks 03020103\_Models\_Revit 030201030101\_RVT\_ARC 030201030201\_IFC\_ARC 03020104\_Models\_Rhinoceros 03020105\_Models\_Solibri 03020106\_Models\_Point-clouds 03020201\_Visualization\_Renderings 03020202\_Visualization\_Images-high-resolution

### 3.2 **Type of field**

In this document structure you first separate out the different fields of study that participate in your project. This type of folder structure can be good if you want to give your users full access to their own are where they are free to move files around as they wish. This file structure is easier to use for the consultants as they have their own area where they can have control over all the files that they are uploading. This file structure is harder to use for the client as files from the different consultants are spread out across each their own folder.

_Example of file structure_

0101\_Information 010101\_Admin 010102\_Contracts 0201\_ARC 02010101\_2D 02010201\_3D\_Archicad 0201020101\_PLN 0201020102\_IFC YYMMDD\_Drawing-title.ifc 02010202\_3D\_Navisworks 02010203\_3D\_Revit 0201020301\_RVT 0201020301\_IFC 02010204\_3D\_Rhinoceros 02010205\_3D\_Solibri 02010206\_3D\_Point-clouds 02010307\_Contracts 0202\_MEP 020201\_2D 020202\_3D 020203\_Contracts 0203\_STR 0204\_LAN

## 4. **Models folder**

With models as documents enabled it is possible to connect models from the models section with documents in the documents section. If new models are made in the models section they will appear in a folder called the models folder. Models can be moved out of the models folder and moved to where you want them to be in the document structure.

Similar to the above examples you can either structure your models by type: 01\_Models -> 0101\_ARC -> YYMMDD\_Model-title.ifc

Or you can structure your models by field of study: 01\_ARC -> 0101\_Models -> YYMMDD\_Model-title.ifc

The best option to choose here depends on if you think your users will be using the [models filter](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291). If you separate models per field of study it might be hard for users to find the 3D models that are mixed in with the other documents of each field of study. If you are confident your users will find the [models filter](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291) you can use this option. If you do not believe your users will use this filter it is better to have all your models in their own models folder so that the user is aware that this folder contains models that can be opened in 3D.
