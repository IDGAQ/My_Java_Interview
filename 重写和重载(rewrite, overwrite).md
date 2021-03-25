# 重写和重载的区别(rewrite, overwrite）
---
---

### 重载：
发生在一个类里面，方法名相同，参数列表不同（混淆点：跟返回类型没关系）\
以下不构成重载
```java
public double add(int a,int b)
public int add(int a,int b)
```

### 重写：
发生在父类子类之间的，方法名相同，参数列表相同
