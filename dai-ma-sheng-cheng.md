# 代码生成快捷键
Ctrl + J
# 常用修饰符

## public static final

键入psf

```
public static final 
```

## public static final int

键入psfi

```
public static final int
```

## public static final String

键入psfs

```
 public static final int 
```

# 常用方法

## main方法

键入**psvm**

```
public static void main(String[] args){

}
```

## System.out.println方法

键入**sout**

```
System.out.println();
```

## System.err.println方法

键入**serr**

```
System.err.println("");
```

# 重写Object类方法

## toString

键入**ps**

```
    @Override
    public String toString() {
        return super.toString();
    }
```

## equals

键入**pe**

```
    @Override
    public boolean equals(Object obj) {
        return super.equals(obj);
    }
```

## hashCode

键入**ph**

```
    @Override
    public int hashCode() {
        return super.hashCode();
    }
```

# 循环

## 生成foreach循环

在要迭代的集合下一行键入 **iter**

```java
List<String> list = new ArrayList<>();
    for (String s : list) {

    }
}
```

## 生成for循环

在要迭代的集合下一行键入 **itli**

```java
List<String> list = new ArrayList<>();
    for (int i = 0; i < list.size(); i++) {
        String s = list.get(i);
    }
}
```

## 生成 iterator循环

在相应的iterator下  **itit**

```java
List<String> list = new ArrayList<>();
Iterator<String> iterator = list.iterator();
while (iterator.hasNext()) {
    String next =  iterator.next();

}
```

## 从左至右迭代数组

在相应数组下 itar

```java
String[] strs = {"a", "b", "c"};
for (int i = 0; i < strs.length; i++) {
    String str = strs[i];

}
```

## 从右至左迭代数组

在相应数组下 litar

```java
String[] strs = {"a", "b", "c"};
for (int i = strs.length - 1; i >= 0; i--) {
    String str = strs[i];

}
```

## 生成 for循环

fori

```java
for (int i = 0; i < ; i++) {

 }
```



