# Reformatting Source Code

## Basic

IntelliJ IDEA lets you reformat source code to meet the requirements of you code style. IntelliJ IDEA will lay out spacing, indents, keywords etc. Reformatting can apply to the selected text, entire file, or entire project.

It is also possible to apply reformatting to the parts of the source code only, using the formatting markers.



## Reformatting the code of a module or directory

To reformat code for a module or directory, follow these steps:

* In the Project tool window, select the module or directory you want to apply you reformatting to.
* Choose **Code \| Reformat Code** on the main menu or press ⌥⌘L. Alternatively, in the Project Tool Window, right-click the directory and from the context menu, select **Reformat Code**
* In the Reformat Code dialog box, specify the necessary options and filters for your reformatting and click **Run.**

## Reformatting the code of the current file

To reformat code for the current file, follow these steps:

* In the editor of the currently opened file, press ⌥⇧⌘L. Note that if you select **Code \| Reformat Code** from the main menu of press ⌥⌘L, IntelliJ IDEA will try to reformat the source code automatically without opening the Reformat File dialog.
* In the Reformat File dialog, specify options for the reformatting and click **Run**.

## Skipping a region when reformatting source code

To enable formatter markers, make sure to select the check box **Enable formatter markers** in comments in the Code Style page of the Settings/Preferences dialog, and type the markers in the **Formatter off/on** fields.

To skip a certain region on reformatting, follow these steps:

* At the beginning of the region, create a line comment \(⌘/\), and then manually type the marker specified in the **Formatter off** field of Code Style pate 
* At the end of the region, create a line comment \(⌘/\), and then manually type the marker specified in the** Formatter on **field of Code Style page 

* Perform code reformatting, as described above.

Alternatively, create a **live template** to surround a block of code with formatter off/on markers, see Creating and Editing Live Templates.

## Example of using formatting markers

**The original source code**

![](/assets/1506555006322.png)

**The code after reformatting**

When the formatting markers are disabled, the origin formatting is broken:

![](/assets/1506555084682.png)

When the formatting markers are enabled, the original formatting is preserved:

![](/assets/1506555129024.png)

