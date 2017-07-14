# 开启assert的支持

```java
public class Assert {

    public static void notNull() {
        assert 1 != 1;
        String name = "jianglei";
    }
}
```

```
java -ea Assert
```

## Idea开启assert

![](/assets/snapshot40.png)

