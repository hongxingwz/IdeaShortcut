# 定义TODO模式和过滤

## 基本

在源码里的TODO项由确切的模式定义

无论什么时候模式被更改或者被添加，IDEA浏览整个项目重新构造TODO项的索引。结果显示在TODO工具窗口，在Viewing TODO items里面描述。

默认的，IDEA提供两种模式：

* \btodo\b.\*

* \bfixme\b.\*

一个更普通的模式看起来像 todo.\*

你可能想浏览更确切的TODO注释类型，并且隐藏其他的。出于此目的，IDEA推荐使用**filters**。这种方法帮助你显示匹配到的更准确的类型

## 定义TODO模式

**定义一个TODO模式，遵守下面通常的步骤**

* 在Settings对话框中打开TODO page
* 在Patterns节，点击**ADD**按钮来创建一个新的模式，或点击**Edit**模式来更新一个已经存在的。然后ADD/Edit Pattern dialog打开
* 在Pattern字段，输入正则表达式来描述一个需要的模式。
* 在Icon列表，选择一个需要的图标，此图标将会标记匹配到的TODO项在TODO tool window里。
* 指定颜色和字体属性，IDEA将会使用他来高亮匹配到的注释在源码里。
* 选择Case sensitive 复选框，如果你想要模式对大小写敏感。



## 定义一个过滤器

来定义一个过滤器将用于展示指定的TODO项类型，遵守下面通常的步骤

1. 打开Settings对话框的TODO page。
2. 打开Filters节，双击Add按钮来创建新的过虑，或Edit按钮来更新一个已经存在的。
3. 在Add/Edit Filter 对话框中，指定过滤器的名字，并选择想要包括的filter。



