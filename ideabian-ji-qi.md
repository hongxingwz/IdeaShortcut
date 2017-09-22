# 编辑器

## 基本

IDEA编辑器是一个很强大的式具用于创建和更改源代码。像其他的IDEA编辑器一样，他支持基本的特性像bookmarks, breakpoints, syntax highlighting, code completion, zooming, folding code blocks,等,许多先进的特性如macros, highlighted TODO items, code analysis, intention actions, intelligent and fast navigation, 和一些其他更多的。

配置你的编辑环境，使用Editor设置而和其子页面。这也有Quick Switch Scheme命令让你改变颜色约束，主题，按键的映射

编辑器是基于tab的。所有的操作都可以从tab的上下文菜单，或从Window \| Editor tabs 执行

## 激活的编辑器

当你打开一个文件用于编辑时，它在其自己tab页打开。你当前工作的编辑器，就是激活的编辑器\(Active actor\)。  
你可以更改激活编辑器的行为使用在主菜单下View \| Active Editor的命令：

![](/assets/1506063716717.png)

可选的，你可以调用相关的命令通过Find Action 或 Search EveryWhere:

![](/assets/1506064049659.png)

## 编辑器区域

![](/assets/1506064111286.png)

1. 编辑区域  
   使用此域区键入和编辑你的源代码。编辑器提供了多个敲代码帮助的场所。在此章下面的节点介绍，和Basic Editing Procedures 和 Advanced Editing Procedures 获得更详细的信息

2. Gutter area  
   左边的gutter提供额外的关于你代码的信息并显示各种图标用于辨别代码结构，bookmarks,断点，scope indicators, change markers 和 code folding lines that let you hide arbitrary code blocks。你可以改变left gutter的行为。

  例如你可以通过隐藏gutter的图标让left gutter更瘦。这对于当前激活的编辑器和其他新创建的编辑器都有效。

  要改变left gutters的行为，使用编辑器设置的Appearance页或**Editor Gutter Popup Menu**

  ![](/assets/1506065013705.png)

  默认的此命令没有映射任何快捷键。你可以创建你自己想要的快捷键在Configuring Keyboard Shortcuts节描述的那样。

3.  聪明的代码提示

  这是编辑帮助特性之一，给你推荐你正在键入的方法名，函数名，标签和其他关键字

4. 文档标签
  
  在你正在工作的多个文档中切换，点击一个标签把其内置放在激活的编辑器前面。在标签中导航，使用快捷键⇧⌘]或⇧⌘[
  
  按处Ctrl / ⌘ 允许你导航到文件路径中的任何一个部分，也可以在外置的浏览器中打开
  
  tab的上下文菜单提供了在一个编辑器中打开的所有可用的命令，例如：
  * 关闭一个或多个标签
  * Pin active tab
  * split and unsplit tabs
  * Manage groups of tabs
  * Navigate between tabs
  * Add to Favorites
  * Move to a changelist
  * Run, or debug in the active editor.
  * Perform local history and version control commands.
  * Perform commands of your own tools.
  
  默认，标签出现在编辑器的上面，你可以改变他们的位置在改变编辑器标签头部的位置一节(Changing Placement of the Editor Tab Headers)


5.  验证侧边栏 / 标记栏

  这个栏在编辑区的右侧，在其最上面显示绿色，红色，黄色依赖于你的代码是否有正常，或包含错误或警告。这个栏也会显示红，黄，白，绿，蓝导航条让你找到准确的发生错误的代码，更变的行，搜索的结果，或TODO项



