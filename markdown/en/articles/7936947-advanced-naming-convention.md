# Advanced naming convention

This article builds upon the following articles: [Simplest naming convention](https://support.catenda.com/en/articles/7845360-simplest-naming-convention) and [Medium naming convention](https://support.catenda.com/en/articles/7936943-medium-naming-convention) The article can be followed without having read these articles but it might be useful to look through them as there might be information about [conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page) that is not mentioned in this article. In this article you will learn all the ways [conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page) can be used.

## 1. **YYMMDD\_Filename\_V.pdf**

By setting up this [convention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) you will learn all you need to know about [naming conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page) so you can pick an choose the [blocks](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) you like for your own [convention](https://support.catenda.com/en/articles/7832559-naming-conventions-page). Say you organize all your 3D models and construction drawings locally.

- You have a dash _( - )_ in the name of the file so in order to separate the different [blocks](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) you will have to use an underscore _( \_ )_ as a [separator](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=in%20document%20settings-,Separator,-%3A%20The%20character).
- These files start with the date of when file was made.

    This is useful to you because even though it usually says this in different places it is just more visual for you to have have your files alphabetically ordered by date of creation.

- After that the you will have the name of the file that can be any length.
- At the end of the file name you have some status to indicate what version of the file you have.

    This part is just some extra text you use to tell your files apart locally. You do not want to see this part of the file name in Catenda Hub document name as it is only useful to you locally and has nothing to do with other people in the project.

- Finally you have decided to make sure you only keep specific file types in this folder.

    You will limit the filetypes to IFC, PDF, DWG, SMC, PL and RVT

### 1.1 **Initial setup**

Documents with the following file names will be used in this article. You can prepare these beforehand or make them when you get to it that part of the article:

_Local files:_ 230219\_Elevation\_Draft.PDF 230219\_Elevation\_Final.PDF aaaaaa\_\_Elevation\_Draft.PDF 230219\_Elevation\_Draft.pdf

_A fourth [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) for the file status_ The date of the file looks a little like the code from the example in the [medium naming convention](https://support.catenda.com/en/articles/7936943-medium-naming-convention) article. The [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) containing the name of the document should also be the same as the filename [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) in that article. The only [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) you need to add that is different from the example from above is a [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) for the status part of your file name.

**Convention setup** For this example you will use the [naming convention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) shown in the image below as a starting point.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b16sm7xd/01-initial-setup.png)

### 1.2 **Custom fields in conventions**

There are three different types of custom fields that are useful in [conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page): [Integer](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22), [Text](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) and [Dropdown](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) [custom fields](https://support.catenda.com/en/articles/6550459-custom-fields-setup) can be used as sources for [convention blocks](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541).

**[Integer custom fields](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) in [conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page)** In the image above the source of the first [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) is set to text. If we try to upload our first file 230219\_Elevation\_Draft.PDF you will see that it uploads without a problem. However, you could also upload six letter instead of numbers like: aaaaaa\_\_Elevation\_Draft.PDF and it would be fine too. In order to limit this to only be numbers make a new [integer custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) called NC\_Date. It is named like that just to keep it organized in the [custom fields list](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=the%20list%20of%20custom%20fields). Then set this [custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup) as the [source](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=has%20an%20extension.-,Source,-%3A%20What%20will) of the first [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) by clicking on the dropdown list where it currently says text and selecting [custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup) you created. You will now see that aaaaaa\_\_Elevation\_Draft.PDF is no longer accepted while 230219\_Elevation\_Draft.PDF is accepted.

**[Text custom fields](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) in [conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page)** For the second [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) you could leave the source as text since any text is accepted here. It is still recommended to use a text custom field that could be named NC\_Filename for future compatibility.

The status can also be any word of any length so make a [text custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) called NC\_Status and set it as the [source](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=has%20an%20extension.-,Source,-%3A%20What%20will) for the third [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541).

For these two blocks you will not notice a difference in the upload process. You will be able to see that the [preview](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_c2f7e24fbc) in different places now reflects the name of the [custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b16sm7xd/02-custom-fields-in-conventions.png)

**[Dropdown custom fields](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) in [conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page)**

**Name same as code** For last [block](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) that contains the [extension](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=The%20name%20of%20the%20file/document%20extension), only a specific set of phrases are to be accepted. To do this make a [dropdown custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) called NC\_Extension. In this [custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup) set the [dropdown options](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=add%20multiple%20options) IFC, PDF, DWG, SMC, PL and RVT. Make the name and the code the same. Be careful that these have to be added one-by-one because a code has to be specified. Now try to upload 230219\_Elevation\_Draft.pdf and see that it will not be accepted. This custom phrase is case sensitive. If you want the lowercase extensions to be accepted as well you have to add those to the [dropdown custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) as well.

**Different name and code** Another good example of what you could do with a [dropdown custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) is having a different name and code. Say you have drawings from mechanical, structural and electrical engineers all with their respective [blocks](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541). In Catenda Hub you want these drawings to all just be called Engineering. What you could do is make a [dropdown custom field](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) [multiple options](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=add%20multiple%20options) that have the name Engineering and the code of the type of engineering you expect to be in the name of the file. When you upload the file then you will see that even though the name of the file had mechanical, structural or electrical in it the name of the document will always say Engineering.

### 1.3 **Document identifier**

[In the beginning of this article](http://You%20do%20not%20want%20to%20see%20this%20part%20of%20the%20file%20name) it was mentioned that it was important that the status part of the file name did not show up as the Catenda Hub document name. That is what the [document identifier](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=block%20to%20do-,Document%20identifier,-%3A) does. When this option is turned off this part of the file name will not be used to make the document name in Catenda hub at all. Try to uploading 230219\_Elevation\_Draft.PDF and then 230219\_Elevation\_Final.PDF Notice how, even though the file name was different, the document name will be the same. This is useful because if the document name is the same, the [naming convention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) will automatically recognize that the second file is a revision of the first.

Finally, this is what your [naming convention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) with [custom fields](https://support.catenda.com/en/articles/6550459-custom-fields-setup) and [document identifiers](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=block%20to%20do-,Document%20identifier,-%3A) should look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b16sm7xd/03-document-identifier.png)
