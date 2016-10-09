# DOL安装笔记

@(DOL)[|Markdown]
**DOL是什么?**
DOL(The distributed operation layer)是一个可以运行编译并行式程序的软件开发框架。
 
**DOL由什么组成？** 
- DOL应用程序编程接口：DOL定义了一系列的计算通信规则，使其可以对SHAPE平台上的分布式并行应用程序进行编程。使用这些规则，程序员无需了解底层架构的详细知识就可以编写程序。 支持移动端 Web；
- DOL功能仿真：程序员可以在上面测试程序的正确性、调整参数。 
- DOL映射优化：用于计算应用程序到SHAPE架构平台上的最优映射。 

**DOL安装**
1. 虚拟机安装Ubuntu 
2. 安装必要环境 
3. 下载dol文件压缩包和systemc文件压缩包，拖入Ubuntu中。 
4. 解压压缩包 
5. 编译systemc 
6. 设置参数  ![](http://ww3.sinaimg.cn/mw690/93ada3f6gw1f8lt9nhikkj20k407lwgj.jpg)
7. 修改路径 home/amy/systemc-2.3.1 这里的路错误会影响到之后的build步骤 
8. 编译DOL，运行第一个例子 

**实验感想**
* 这次实验主要是配置实验环境，总体来说就是按照PPT上来做，但是我在修改路径时打多了一层文件夹，导致后面build的时候失败了。

-------------------
