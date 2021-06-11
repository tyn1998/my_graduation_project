# 总结与展望

本章总结课题的主要工作，指出其中的创新与不足，并对课题所处的蛋白质相互作用研究领域寄予展望。

## 课题总结

课题基于1840个物种的蛋白质相互作用数据，引入并计算了一些度量蛋白质相互作用网络的指标，之后基于网络度量进行蛋白质相互作用的演化研究。最后，课题对蛋白质相互作用网络及网络度量进行可视化。

### 课题的主要工作

（1）梳理数据集结构，并考察数据集来源；

（2）基于SNAP实例化蛋白质相互作用网络；

（3）分别从整体和局部层面引入度量蛋白质相互作用网络的指标；

（4）实现（3）中指标的计算；

（5）基于网络度量，进行蛋白质相互作用的演化研究；

（6）基于Web，对研究成果进行交互式可视化。

### 创新之处

在模拟网络故障时（§3.1.2），除了使用随机结点移除策略来模拟蛋白质发生无义突变和因资源缺失而溃败的情况外，课题还按结点中介中心性、点度中心性的大小来移除结点，模拟极端情况下的网络故障。

在基于Web的可视化界面设计方案中，课题采用计算布局和渲染图形分离的策略，使浏览器能够流畅加载和呈现结点以万计、边以十万计的大规模网络。

### 不足之处

课题在度量蛋白质相互作用网络时引入并计算了许多指标，但其中有不少指标未被赋予有意义的生物学解释。

## 展望

蛋白质相互图谱测绘技术可以追溯到上世纪90年代。从21世纪初，蛋白质纯化、质谱、基因编辑技术等方法学改进，使科研人员的制图工艺日益精细，加速了捕获所有蛋白质相互作用这一伟大挑战的进程。

处理大量蛋白质相互作用数据的手段势必更加先进。蛋白质组学将与计算机科学更加紧密联系起来。人们对蛋白质相互作用网络的局部研究将更深入，对蛋白质相互作用内部机理的理解也将越来越深刻。