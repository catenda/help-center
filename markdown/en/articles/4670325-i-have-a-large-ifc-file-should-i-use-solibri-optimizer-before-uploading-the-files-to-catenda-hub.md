# I have a large IFC file. Should I use Solibri Optimizer before uploading the files to Catenda Hub?

The answer is no. If your file becomes large its better to just [zip the files before uploading](https://support.bimsync.com/hc/en-us/articles/360009995879) instead. Solibri Optimizer will in some cases corrupt the file so it doesn't pass through the various import steps in Catenda Hub. An optimize file will not become quicker to browse in Catenda Hub as we will store information in optimized formats regardless of the state of the file on import.

If you have a file that fails on upload please check the file header for traces of Solibri Optimizer (open in notepad or similar and look at the first 10 lines of the file header) If the failing file is optimized please try with the original file instead.

![mceclip0.png](https://raw.githubusercontent.com/catenda/help-center/main/images/p8sgh6tt/01-intro.png)

(this file has been through the Solibri Optimizer)
