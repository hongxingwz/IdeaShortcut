# 剪切，复制和粘贴

## 基本

IDEA提供大量的处理剪切板的操作。你可以复制，剪切且粘贴选择的文本，一个路径至一个文件，一个符号的引用或一行代码。

因为IDEA使用系统的剪贴板，所以你可以在应用间复制和粘贴东西。当在粘贴剪贴板的东西时，IDEA会移除文本的格式和任何特殊的符号

**Paste**命令会聪明的理解想要插入什么，如果你粘贴一个对符号的引用，他们分析可能的导入，引用，等等。IDEA提供必要brackets and places the caret at the appropriate insertion point.

**Paste Simple**命令帮助你粘贴任何剪贴板的东西作为纯文件，没有任何解析。

IDEA允许你剪贴板堆加，这代表着你可以存储多个剪贴板入口并且访问他们以一个单一的快捷键。可以在剪贴板中存储的入口的数量可以在Settings/Preferences的Editor页设置

## 复制一小段文本

作下面的其中之一：

* 在主菜单中，选择**Edit \| Copy**
* 按**⌘C**
* 在工具栏点击**Copy**按钮

注意⌘D快捷键复制光标所在的一整行

## 复制路径到文件

作下面的其中之一：

* 打开一个需要的文件，然后选择 Edit \| Copy Path 在主菜单 或 ⇧⌘C
* 在Project tool窗口中在上下文的菜单中选择**Copy Path**

## 复制一个引用或符号到一行

* 在编辑器中打开需要的窗口
* 把光标放在需要的行
* 作下面的其中之一：
  * 在主菜单中，选择**Edit \| Copy Reference**
  * 在光标的上下文菜单中， 选择** Copy Reference**
  * 选择 ⌥⇧⌘C

IDEA创建字符串的格式依赖于符号。例如：

`/MetersToInchesConverter.java:14`用于一个java类\(格式&lt;full qualified path&gt;:&lt;line number&gt;\)

`java.io.PrintStreamp#println(java.lang.String)`用于一个java方法\(格式&lt;full classname&gt;.&lt;method\_signature&gt;\)

## 剪切一段选中的文本

* 选择需要的文本
* 作下面的事情之一
  * 在主菜单，选择**Edit \| Cut**
  * 按 ⌘X
  * 在工具栏中按**Cut**按钮

## 从剪切版中粘贴最后一个入口

* 把光标定位到你想要粘贴内容的地方
* 作下面的其中之一：
  * 在主菜单，选择 **Edit \| Paste**
  * 按⌘V
  * 点击在工具栏中的**Paste** 按钮



## 从剪切版中作为简单的文本粘贴最后一个入口

作下面的其中之一：

* 在主菜单中，选择**Edit \| Paste Simple**
* 按⌥⇧⌘V

## 从剪贴板中粘贴一个指定的入口

* 在主菜单中，选择 **Edit \| Paste from History** 或按 ⇧⌘V
* 在 **Choose Content to Paste**对话框中，选择一个需要的入口 ，并点击确定。

剪贴板的深度可以在Settings/Preferences 的 Editor页中的Limits节指定。当指定的数量被执行时，老的入口会被删除。



