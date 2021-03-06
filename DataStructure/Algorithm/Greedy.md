# 贪婪算法
设计算法以实现给定问题的最佳解决方案。在贪心算法方法中，决策是从给定的解决方案域做出的。由于贪婪，选择了似乎提供最佳解决方案的最接近的解决方案。

贪心算法试图找到一个本地化的最优解决方案，最终可能导致全局优化的解决方案。但是，通常贪婪算法不提供全局优化的解决方案。

# 计数硬币问题
这个问题是通过选择最不可能的硬币来计算到期望的值，并且贪婪的方法迫使算法选择最大可能的硬币。如果我们提供₹1,2,5和10的硬币，我们被要求计算₹18，那么贪婪的程序将是 -

1 - 选择一个₹10硬币，剩余计数为8

2 - 然后选择一个₹5硬币，剩余计数为3

3 - 然后选择一个₹2硬币，剩余计数为1

4 - 最后，选择一个₹1个硬币可以解决问题

虽然，它似乎工作正常，但这个数量我们只需要选择4个硬币。但是，如果我们稍微改变问题，那么相同的方法可能无法产生相同的最佳结果。

对于货币系统，我们有硬币值为1,7,10的值，计算值为18的硬币绝对是最佳的，但对于15的计数，它可能会使用超过必要的硬币。例如，贪婪的方法将使用10 + 1 + 1 + 1 + 1 + 1，总共6个硬币。而只使用3个硬币（7 + 7 + 1）就可以解决同样的问题

因此，我们可以得出结论，贪婪的方法选择了立即优化的解决方案，并且可能在全局优化是主要问题的情况下失败。

# 栗子
旅行推销员问题
Prim的最小生成树算法
Kruskal的最小生成树算法
Dijkstra的最小生成树算法
图 - 地图着色
图 - 顶点覆盖
背包问题
作业调度问题
