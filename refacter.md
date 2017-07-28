### 重构文件名

Shift + F6

### 重构类名，方法名， 变量名

两次Shift + F6  
第一次 给你个提示  
第二次 弹出一个dialog，请你改名字

# 复制

F5

# 移动

F6

# 提取变量

mac: **Cmd + Alt + V**

```
BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
```

提取完之后

```
InputStreamReader in = new InputStreamReader(System.in);
BufferedReader reader = new BufferedReader(in);
```

### 重构符号的名称， 返回值， 修饰符等

Shift + Alt + Cmd + T

![](/assets/import8.png)



