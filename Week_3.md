# 1. Algorithm

这次的题很有意思，想了很久才想出来。写了篇博客，不单独列这了

[LeetCode 940 Distinct Subsequences II 解题思路](<https://blog.csdn.net/VVBBBBB/article/details/89413107>)

# 2. Review

Medium: [How Much Can We Afford to Forget, If We Train Machines to Remember?](<https://medium.com/aeon-magazine/how-much-can-we-afford-to-forget-if-we-train-machines-to-remember-73bc9b21a13c>)

​	主要讲历史社会和现代社会发展中的同与不同。

​	现在的人们对一些技能以及选择性的遗忘，已不清楚也不用去关系如何去建房子、养殖、Farming了。看到这里，我想起来之前看的《架构师之路》的开篇，一开始每个人所所有力所能及之事，随着文明不断向前发展，每件事要花费的时间也越来越多。随着而来的进化是协同、分工，不同的人分别做自己擅长的事情，而且也能更加专注，大大提高了部落的生产效率。

​	作者在这里认为，我们也是处于这样一个时期，内容越来越多，越来越丰富。然而，要记住所有的事情，实际上并不可能。一是时间不允许，二是记住那么多东西干嘛呢。因而要将事情分包出去，解放大脑的占用，发挥大脑应有的创造力。但与此同时，内容提供平台（如Google搜索等）作为一项基础设施，已不可或缺，需要保障其运行的稳定性，两者之间形成一个依赖关系。

​	看完了这篇文章，突然觉得现代社会的发展历程和金字塔建设有及其相似之处，从一个人开始到部落、再到城市、国家、全球。逐步发展起来，而且在这个发展的基础上继续创造更大的成就，之后再将这个成就作为下一阶段发展的基石。现有第一步，再有第二步，才能出现其他的。

# 3. Tips

[Prof-UIS](<http://www.prof-uis.com/>)

这个框架对MFC的类库进行了大量的封装和扩展，里面的结构充分显示出了其设计的充分性和完备。目前还在进行Prof-UIS框架代码的阅读和学习，有不少有意思的特性。虽然这方面了解得不多，但里面对设计模式和设计原则的运用肯定不少。

- 菜单动态生成——通过配置菜单的ID号
- 工具栏、状态栏绑定——通过引入ParentClass，在状态栏等的类中进行配置——这个方法确实有点厉害的…
- CWnd中的OnCmdMsg函数，通过ID、notifier等来确定发送消息的控件主体，并对其配置进行修改。
- 配置的导入导出——到注册表中、文件（CArchive类）
- 对TreeCtrl功能的扩展和丰富——富文本、进度条、按钮、组合框等

Windows DLL相关：

​	dumpbin.exe 中/exports /link等指令的使用。



# 4. Share

Blog: [散列表——Hash Table](https://blog.csdn.net/VVBBBBB/article/details/89428146)

之后是关于最短路径算法的。