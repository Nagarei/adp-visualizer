# Visualizer

## URL
https://nagarei.github.io/adp-visualizer/index.html

## input

```
S_x S_y
N
x_0 y_0 x_1 y_1
x_2 y_2 x_3 y_3
 :
x_{2N-2} y_{2N-2} x_{2N-1} y_{2N-1}
M
```

- N >= 2
- x_i, y_i は整数


## output

```
p_1 p_2 ... p_{2N}
```

- 空白区切り
- 0 <= p_i < 2N
- { p_1, p_2, ... , p_2N } は順列


## tips
- 全然テストをしていないのでバグ報告大歓迎です．
- riantkb さんの [tsp-visualizer](https://github.com/riantkb/tsp-visualizer) を参考にさせていただきました．
