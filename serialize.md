#Serializable接口,不提示生成,serialVersionUID
当一个类在实现了Serializable接口时，Idea默认是不会警告你没有生成serialVersionUID。

怎样才能设置让其提示生成serialVersionUID呢？

* File >> Settings 搜索inspections,选中在右侧搜索框搜索 serialization issues,将Serializable class without 'serialVersionUID' 勾选，然后设置为Waring 或 Error， 最后点击确定
![](/assets/snapshot15.png)

* 将光标移动到实现了Serializable接口的类名处，Alt + Enter 就会提示 'Add serialVersionUID',点击确定就可以添加了。

