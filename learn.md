### 2026年8月29日

```c++
child_height = (dad_height + mom_height) * 0.54;
```
提示“Narrowing conversion from 'double' to 'float'”
问题：0.54 是 double 类型，计算结果是 double，赋值给 float 会丢失精度。
改进方案：使用 0.54f 表示 float 常量
```c++
child_height = (dad_height + mom_height) * 0.54f;
```

浮点数输出保留n位小数用“%.nf”表示

### 2026年8月30日

C语言中的关键字
```c++
auto      double  int        struct
break     else    long       switch
case      enum    register   typedef
char      extern  union      return
const     float   short      unsigned
continue  for     signed     void
default   goto    sizeof     volatile
do        while   static     if
```

#### 所有函数都要记得加“return”！！！