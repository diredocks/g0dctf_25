# 只有减法的世界

你在一个奇怪的 REPL 里，输入表达式后它会返回运算结果，但好像不是我们习惯的方式在计算。

你试试看输入：

```
(- 4 2)
```

返回了什么？

```
=> 2
```

好像很正常？

那试试看加法呢？

```
（+ 4 2）
```

不太友好了 `Failed to evaluate expression...`

这个世界的运算器只认识 `(`, `)`, `-`, `1` 和一个奇怪的关键词 `lambda`

那么问题来了，怎么让下面的表达式返回 42 呢？

```
((你的代码将会在这里) 24 18)
```

又或者是其他的数字？
