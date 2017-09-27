# Splitting String Literals on Newline Symbols

You can split a string literal on newline symbols\(`\n`\) by using the Break string on '\n' intention action. That is, a string literal in a code fragment like this:

```java
String s = "Hello, \nWorld!";
```

can be easily transformed into corresponding concatenation:

```java
String s = "Hello, \n" + 
    "World!";
```

To do that:

* Place the cursor within the literal of interest.
* Click the yellow light bulb icon or press ⌥⏎, and select **Break string on '\n'**

![](/assets/1506553290969.png)



