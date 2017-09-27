# Joining Lines and Literals

## Basic

IntelliJ IDEA makes it possible to concatenate two unselected or several selected lines  into one, removing the extra spaces, and providing the proper syntax.  This operation smartly analyzes the lines being joined and treats them accordingly. For example, you can join lines of code, lines of comments, field declaration and initialization.

## Joining lines

* Place the caret on the line, to which the other lines should be added.

![](/assets/1506527517980.png)



* Sequentially press ⌃⇧J keyboard shortcut, until all fragments are joined in a single line.

![](/assets/1506527587274.png)

![](/assets/1506527604961.png)



## Joining string literals

* Select the lines with string literals that should be joined.

![](/assets/1506527747198.png)

* Press ⌃⇧J keyboard shortcut. All redundant characters\(spaces, quotes, and plus signs\) are gone.

![](/assets/1506527760725.png)



## Examples

Joining a field or variable declaration and assignment:

![](/assets/1506527911245.png)

Pressing ⌃⇧J produces the following result, with the unwanted spaces and variable name is the second line removed.

![](/assets/1506527969211.png)

Consider the following pair of statements:

![](/assets/1506528011706.png)

Press ⌃⇧J to join these lines into a correct single-line statement.

![](/assets/1506528056555.png)

