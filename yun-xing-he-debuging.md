# 运行和debugging

只要你创建了Run/Debug configuration通过选择Run \| Edit Configurations从主菜单中，你就可以运行和debug你的代码了

| 动作 | 快捷键 |
| :--- | :--- |
| Run | ⌃R |
| Debug | ⌃D |

当你处于debug模式时，你可以通过执行**Evaluate expression**工具执行任何表达式，通过按⌥F8进入。这个工具与编辑器提供相同的代码完成功能，所以很容易键入任何表达式。

一些时候你想进入一个特别的方法，但不是第一个将被调用的方法，使用**Smart step into**通过按⇧F7来选择一个指定的方法

| 动作 | 快捷键 |
| :--- | :--- |
| 切换断点 | ⌘F8 |
| step into | F7 |
| Smart step into | ⇧F7 |
| Step over | F8 |
| Step out | ⇧F8 |
| Resume | ⌘⌥R |
| 执行表达式 | ⌥ F8 |



## 重新加载更改和热替换

一些时候，你需要作一些小的改变到你的代码里而想停止掉你的进程。因为Java VM 具一个热替换的特性，IDEA会自动的处理这些当你调用**Make**时



