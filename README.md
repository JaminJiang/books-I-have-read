# books-I-have-read
那些年我看过或想看的书籍。
***
#机器学习

##《Machine learning in Action》
4星 

有本中文版，用过里面的ridged regression，看过英文的classification部分。代码写得一般，但没有用到多少面向对象的东西。理论不足，比如逻辑回归部分代码直接使用了对w求导后的公式，而不带说明，svm章中对smo算法的毫无描述直接上代码。带我进入机器学习的书。

##《Hands-On machine learning with Scikit-learn & Tensorflow》
4星半

现在看到第四章，非常不错，学完整理成思维导图（参考收藏的github 项目）。

##《Building Machine Learning System with Python》
4星 

没看，代码零零碎碎，但是很多机器学习中的细节问题，tricks都考虑进去了，所以以后抽时间看看吧。

##《集体智慧编程》
4星 

协同过滤、聚类、搜索与排名（点击中学习）、优化问题等，因为代码不规范而弃读。

##《Spark 机器学习》
4星 

买了新书一直没看。python语言，以后得看！

***
#工作

##复习C++的建议路线
[C++对象模型博客](http://www.cnblogs.com/skynet/p/3343726.html) -->[How to program in C++](http://cs.fit.edu/~mmahoney/cse2050/how2cpp.html) --> 《Effective C++》-->《剑指Offer》 -->《程序员面试宝典》（有时间的话）--> [July编程艺术](http://www.cnblogs.com/v-July-v/category/366043.html)
##复习Python的建议路线
[Python编程最佳实践](http://www.kuqin.com/shuoit/20160121/350192.html) --> [Python自省（反射）指南](http://www.cnblogs.com/huxi/archive/2011/01/02/1924317.html) --> [让你的Python代码更Pythonic](http://www.jb51.net/article/56271.htm) --> 《QUANTITATIVE ECONOMICS with Python》 --> 我的“awesome机器学习”

##《Effective C++》
4星半

讲解的细致系统，看完之后对C++有了较深的认识，可惜忘得差不多了，有机会再看。
##《剑指offer》
4星半 

使用C++语言，主要关于算法，算法编写的很到位，而且对边界变量考虑很周全，找工作之前必重温。

##《编程珠玑》
4星

2016/02/20-02/27间看完。

介绍了编程的过程：①通过深入挖掘定义了正确的问题，②通过仔细选择算法和数据结构平衡了真正的需求，③通过程序验证技术写出了优雅的伪代码，并且对其正确性相当有把握，④万事俱备，只欠不起眼的编程了。

几种重要的算法设计技术：
保存状态，避免重复计算。动态规划；累积求差计算i到j元素的和。
将信息预处理至数据结构中。
分治算法。二分法。
扫描算法。数组有关的问题，通常可以考虑从i-1扩展到i的思路。

其他笔记参考我的日记1602.docx。


##《C++ concurrency in action》
3.75星 

2018-07-07 看完
原版后面关于实现并发数据结构的部分较难，中文版本翻译灾难。就看懂的部分来看，是本好书。了解了C++ 11中并发的用法，mutex同步data，condition_variable、future、promise、packaged_task、async 同步operation。了解设计并发结构的基本思路——对成员函数加锁，锁在时间空间上细粒度。另外附录部分关于C++ 11的部分、关于多种并发库的对比等总结的不错。

##《程序员面试宝典》
3星半 

排版很差，代码分为左右两节，貌似还有些错误，没看下去。不过以后还是得过一遍。


##《七周七并发》
3星 

太多Cloure语言的内容，不和我的口味。

##《亿级流量网站架构》
3星 

目录不错，内容太差，大多是代码和配置文件堆砌。

##《程序员修炼之道-小工到专家》
3星半 

对我而言太理论化，不懂。

##《Cracking the code interview 5th》
4星 

网上有各种语言的代码<https://github.com/gaylemcd/ctci>，之前看了一部分，感觉没有中文的剑指offer好。后面找工作必须得过一遍。
***
#杂

##《设计模式》
4星 

没看完第一章，以后可以看。

##《数学之美》
4星半 

计算机中的数学之美，讲得浅显易懂，科普类，新手必读。

##《浪潮之巅》
四星 

科普类读物，权当谈资。

##《开发自己的搜索引擎——Lucene+Heritrix》
四星 

教小朋友的时候用到的书，不过现在好像用ElasticSearch。
***
#Quant

##《QUANTITATIVE ECONOMICS with Python》（简称py-quant-econ）
4星半 

内容全面，numpy、scipy、pandas、the need for speed等。使用的是notebook排版，效果极好。关于quant的内容分两部分，introductory applications和Advanced applications，略难，当时没看懂才弃读，到头来还是得捡起来。

##《Yves Hilpisch-Python for Finance_ Analyze Big Financial Data》
4星 

本书关于python数学、统计、随机等讲解的很到位，后面的内容也都是面向对象的代码。

##《量化投资策略与技术修订版-丁鹏》
4星 

量化协会主席的书，虽然没多少代码，但是分析的过程很有道理。

##《Yuxing Yan-Python for Finance》
3星 

太多关于python基础的，所以没看。

#Misc

##《学术研究，你的成功之道》
3星半

关于学术研究的小书，俱往矣。


***
#awsome awsomes

##awsome 机器学习
机器学习最好的资料！spark、kaggle、scikit、等资料。<http://nbviewer.jupyter.org/github/donnemartin/data-science-ipython-notebooks/tree/master/>新加了deep-learning模块，写完就去看~ 

机器学习次好的资料！过程全面，数据预处理、可视化、交叉验证、参数最优化等。<http://nbviewer.ipython.org/github/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb>
斯坦福大学机器学习课程个人学习笔记 （我的网盘中有） 主要讲解理论，是不错的资料。

##awsome python
参考我的360浏览器收藏夹，尤其是其中廖雪峰的官网<http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000>,里面有完整的Python web开发过程和示例，让我对网页，网络，并行等有了更进一步的理解，找工作必读。

##awsome quant
参考我的360收藏夹-0710量化投资，主要是quantopian上的内容。 

[math-finance-cheat-sheet] (https://github.com/daleroberts/math-finance-cheat-sheet/blob/master/math-finance-cheat-sheet.pdf)

##awsome English
百词斩<http://www.baicizhan.com/words/slash>-背单词不二之选。 

新编英语口语<http://www.doc88.com/p-99614752011.html>这本书中的文章不错。

##awsome 思维导图
一张金字塔思维导图，待会记得看。

#awsome Java
美食天下项目，当年解救我于课程设计中。

#awsome 学科
##《简单的逻辑学》
3星星半

了解基础，看完也没有什么恍然大悟的感觉。论证结构：演绎论证（联言论证、选言论证、条件论证、三阶段）、归纳验证。错误论证：形式谬误（否定前件、肯定后件、中项不周延）、非形式谬误（以笑饰非、以泪掩过、情感误导）。


#awsome 生活
冷读术（度盘） 

斗地主（度盘） 

羽毛球-[影子传说](http://www.ssstjy.com/yumaoqiu/yumaoqiu.htm)，gif讲解
