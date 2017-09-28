# Adding, Deleting and Moving Code Elements

## Adding lines

**To add a line**

* Press **⇧⏎ **to add a new line after the one where the caret is currently located and move the caret to the beginning of this new line.

For instance, you have typed some text:

![](/assets/1506560798667.png)

Press ⇧⏎ to start the next line immediately:

![](/assets/1506560850313.png)

* To add a line before the current one, press ⌥⌘⏎



## Duplicating lines

**To duplicate a line or fragment**

* Place the caret at the line to be duplicated, or **select** the desired fragment of text.
* Press ⌘D



## Deleting lines

**to remove a line**

* Press  ⌘⌫ to delete the line at caret.



## Moving lines

**To move a line**

* Place the caret at the line to be moved.
* Do one of the following:
  * On the main menu, choose **Code** \| **Move Line Up** or **Code \| Move Line Down**
  * Press ⌥⇧↑ or ⌥⇧↓

IntelliJ IDEA moves the selected line one line up or down, performing the syntax check. For example:

![](/assets/1506561482521.png)

After moving line at caret:

![](/assets/1506561511848.png)

## Moving statements

**to move a statement up or down**

* Select a statement to be moved, or just place the caret at the first or last lines of a multi-line statement. Note that if moving a statement is not allowed in the current context, the commands will be disabled.
* Do one of the following:
  * On the main menu, choose **Code \| Move Statement Up/Move Statement Down.**
  * Press ⇧⌘↑ or ⇧⌘↓

If you apply the same commands to a line at caret, or a to a selection, it will be moved one line up or down.

IntelliJ IDEA moves the selected statement above the previous one, or directly underneath the next one, performing the syntax check. For example, place the caret at the method declaration:

![](/assets/1506561988409.png)

After moving the statement:

![](/assets/1506562019360.png)



## Moving code element left or right

**To move code element to the left or to the right**

* Place the caret at the desired code element, or select the elements to be moved.
* Do one of the following:
  * One the main menu, choose the commands **Code \| Move Element Left **or **Code \| Move Element Right**
  * Press ⌥⇧⌘← or ⌥⇧⌘→

Examples of code elements for which this functionality is currently implemented:

* **Java**: method invocation arguments, method declaration arguments, enum constants, array initiazlizer expressions.

![](/assets/1506562469078.png)

* **XML**: tag attributes

![](/assets/1506562536271.png)

* HTML: tag attributes.

![](/assets/1506562579612.png)



