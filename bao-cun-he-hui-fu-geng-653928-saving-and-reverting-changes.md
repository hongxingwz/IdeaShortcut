# 保存和恢复更改

## 介绍

When working with IntelliJ IDEA, you don't need to worry about saving changed files: all changes are auto saved.

Unwanted changes can be undone at any stage of you development workflow. Any file or directory can be reverted to any of the previous states.



## 什么时候IntelliJ IDEA会自动保存文件？

Autosave is initiated by:

* Compiling a project, a module or a class
* Starting a run/debug configuration
* Performing a version control operation such as pull, commit, push, etc.
* Closing a project
* Quitting the IDE

In fact, there is a lot more autosave triggers, and only the most important ones are mentioned above.



## 关闭自动保存行为

The following options are available for tuning the autosave behavior\(File \| Settings \| Appearance and Behavior \| System Settings\)

## 以一个不同的文件名保存文件

There is no **File \| Save As** command in IntelliJ IDEA. To save a file under a different name or in a different directory, use** Refactor \| Copy** or **F5**.

## 恢复更改

You can undo changes by using **Edit \| Undo** 或 ⌘Z。 To revert files to their previous states , use Local History and corresponding version control functionality.



