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