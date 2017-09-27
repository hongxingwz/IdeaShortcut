# 多重光标
在此页

* 基本
* 添加，删除和克隆光标
* 粘贴和复制

##基本

IntelliJ IDEA 支持多重光杆。编辑器主要的行动，例如键盘导航，文本插入，删除等。都适用于每个光标。在线模板和自动完成也支持。

可以添加或删除光标；每个编辑器选项卡中至少使终存在一个光标

最近添加的光标被认为是**主光标**。编辑器的行高亮仅适用于主光标

## 添加，删除和克隆光标

**添加光标，作下面的其中一下**

* 按Shift + Alt 然后点击鼠标的左键
* 按Ctrl\(Windows or UNIX\)  / Alt\(macOS\)两次然后不释放，按上或下方法键

  The new carets are added to the specified locations, according to setting of the **Allow placement of caret after end of line** check box:

![](/assets/1506522514966.png)

**要删除光标，作下面的其中一项**

* 按Esc 删除所有已经存在的光标，除了主光标。
* 按Shift + Alt 然后点击鼠标左键来删除

**克隆 an existing caret upward or downward, do one of the following**

* Press ⇧⌘A, type **Clone caret**, and choose the desired action from the suggestion list:

![](/assets/1506522963311.png)

Note that by default these actions are not bound to the keyboard shortcuts. You can do it yourself, as described in the section Configuring keyboard shortcuts.

The primary caret is propagated upwards or downwards:

![](/assets/1506523048712.png)

## 粘贴和复制
When a text with multiple cursors is copied ⌘C or cut (⌘X), selections for each caret are placed to the clipboard. On paste  (⌘V),text from the clipboard is split into lines.



