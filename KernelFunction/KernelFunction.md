# 核函数（Kernel Function）
## 出发点：
低维很难解决的问题，一旦把维度升高之后，原始一个很难的问题就能变成一个可解决的问题了。但是维度升高，计算量就变大了。
## 线性核函数（Linear Kernel Function）
线性核函数对数据不做任何变换：$K$($x_i$, $x_j$) = $x_i^T$·$x_j$

当特征已经比较丰富了，样本数据量巨大，需要进行实时得出结果时使用。

不需要设置任何参数，直接就可以用了。

越简单的模型越稳定。对于复杂的模型，可能会出现过拟合的现象。

## 多项式核函数

需要给定3个参数：

一般情况下2次的更常见：

## 高斯核函数（Gaussian Kernel Function）

高斯核函数 (Gaussian kernel)，也称 径向基 (RBF) 函数，就是某种沿径向对称的标量函数，用于 将有限维数据映射到高维空间。通常定义为空间中任意一点x到某一中心点x'之间的欧式距离的单调函数，可记作k(||x-x'||),其作用往往是局部的 , 即当x远离x'时函数取值很小。如果X和Y很相似，那结果也就是1了，如果很不相似那就是0。

