# 概述
图形是一组对象的图形表示，其中一些对象通过链接连接。互连对象由称为顶点的点表示，连接顶点的链接称为边。

形式上，图形是一对集合（V，E），其中V是顶点集合，E是边缘集合，连接顶点对。看看下面的图表 -


![](./images/graph_basics.jpg)

在上图中，

V = {a，b，c，d，e}

E = {ab，ac，bd，cd，de}

# 图数据结构
数学图可以用数据结构表示。我们可以使用顶点数组和二维边数组来表示图形。在我们继续前进之前，让我们熟悉一些重要的术语 -

顶点 - 图形的每个节点都表示为顶点。在以下示例中，标记的圆圈表示顶点。因此，A到G是顶点。我们可以使用数组来表示它们，如下图所示。这里A可以通过索引0来识别.B可以使用索引1来识别，依此类推。

边 - 边表示两个顶点之间的路径或两个顶点之间的线。在以下示例中，从A到B，B到C等的线表示边。我们可以使用二维数组来表示数组，如下图所示。这里AB可以在行0，列1，BC处表示为1，在行1，列2处依此类推，依此类推，将其他组合保持为0。

邻接 - 如果两个节点或顶点通过边缘相互连接，则它们相邻。在以下示例中，B与A相邻，C与B相邻，依此类推。

路径 - 路径表示两个顶点之间的边缘序列。在以下示例中，ABCD表示从A到D的路径。

![](./images/graph.jpg)

# 基本操作
以下是图表的基本主要操作 -

添加顶点 - 向图形添加顶点。

添加边 - 在图的两个顶点之间添加边。

显示顶点 - 显示图形的顶点。
