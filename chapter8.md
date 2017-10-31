# [8. Wave Function Collapse](https://github.com/go-ego/riot)

### 标签：

`quantum mechanics` `c#`

### 简介：

Wave Function Collapse，直译：波函数坍缩，是一个由量子力学理论启发，能够从单个简单输入位图生成复杂位图的程序。如下图，左侧为输入的位图，右侧为不同参数N下生成的位图：
![](https://camo.githubusercontent.com/3ea3b800ee9de783abea49612a40beeda97879de/687474703a2f2f692e696d6775722e636f6d2f67317947764c372e706e67)

其生成规则的特点为局部相似性(local similarity)，有如下性质：
- 输出中每个NxN模式的像素至少在输入中出现一次。
- NxN模式在输入中的分布应该类似于NxN模式在足够多的输出上的分布。

生成算法主要思想是：

- 将整个输出按参数N划分为数个区域，每个区域设为未观察的叠加状态。
- 进行观察，每次观察选择具有非零最小熵的区域，对其进行“坍缩”（通过其确定的状态系数在输入中选择一个N*N区域）并传播观察到的信息。重复观察直到找不到相应区域，此时输出已经完全确定。

算法细节请参见项目主页及其代码。

这个程序进行拓展后，输入可以不止一张位图，能够用于生成游戏地图、PCB布线等。且不止2D图形，也能生成3D图形。详情请参见项目主页。

## 项目地址：

https://github.com/mxgmn/WaveFunctionCollapse

## 参考链接：

- https://github.com/mxgmn/WaveFunctionCollapse/blob/master/README.md
- 作者：侯炜
