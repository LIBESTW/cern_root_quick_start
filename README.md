#写在前面
##关于作者
&emsp;粒子物理专业高能物理实验方向研究生在读，即将毕业。如果你对此项目有兴趣，非常欢迎加入我们.目前参与此项目的还有我的同学[@daihk](https://github.com/daihk)。如果大家发现什么错误，请一定
##ROOT是什么？
&emsp;ROOT是一款数据分析软件，在实验物理特别是高能物理中应用非常广泛。它几乎提供了实验物理所需要的所有功能，包括海量实验数据处理，统计分析，做图，以及数据存储。ROOT基本全部由c++编写，同时又整合了其他语言接口，比如Python与R。
##ROOT适合的用户？
&emsp;ROOT几乎适合所有实验物理工作者。特别是需要数据处理，以及用数据做图的科研人员。可以说ROOT是实验物理科研人员的必备工具，如果你恰好就是其中一员，且打算长期从事这个行业，不管你的师兄师姐们有没有用ROOT,对于学ROOT这件事，不要有任何犹豫。
##手册主要目的
&emsp;有点讽刺的是，本手册并不能满足实验物理科研人员的需求。这本手册只是在我使用ROOT的这两年时间里的一点个人心得。**它跟官方手册的区别在于，官方手册是尽可能的把每一个可能用到的功能都展示给用户，
而本手册的目的只是尽可能有侧重点的，介绍我们最常用的一些工具，以此来帮助用户尽可能快的入门。本手册对于一个真正做实验物理的科研人员来说，是远远不够的。**
手册的目的，可能仅仅是满足一些，并不长期工作于一线的物理工作者，他们并不需要把ROOT作为自己处理数据的主要工具，可能只是偶尔想用ROOT算个数据，画个图。
本手册也适合想要学习ROOT但是一开始感觉困难难以入门的学习者，因为它几乎涵盖了我两年来使用ROOT的所有常用功能，掌握本手册出现过的功能，就可以应付大部分工作。
希望每个读者在学习完本手册后，能满足平时一些简单的需求，对ROOT有个初步的了解,入门之后,再进一步学习的话也会容易很多。

##必须要讲一下的问题
####1. 英语
&emsp;本手册是中文，仅仅是为了最快速的入门。再次强调一遍，**如果你是实验物理工作者，请务必去查看官方手册获取更多更详细内容，本手册的内容非常粗略且不详细.**
####2. C++
&emsp;我认识很多人，在被迫使用ROOT时完全不会或者几乎完全不会c++,包括我。不会c++,能不能使用ROOT？这跟不懂英文能不能在一个英文国家生活大致类似，可以活下去，但是肯定非常不方便，
去超市买东西要看着图片买，还很可能买错了。c++也是实验物理人员的必备技能，所以，如果你现在还对c++不了解，打算以后长期从事这个行业，对学c++这件事，也不要有任何犹豫。  
毕竟。。。。学物理，当你猛然间发现博士毕业找不到工作的时候,会c++还可能救你一命...  
####3. 学习ROOT方法
1. 多看栗子，在$ROOTSYS/tutorial下面有大量优秀且注释详细的栗子,大部分简单工作都可以从栗子里面用法，本手册我们也是主要以栗子来讲解。  
2. 官方手册，你可以在这里[ROOT User Guides and Manuals](https://root.cern.ch/root-user-guides-and-manuals)找到各种适合你的手册.  
3. 另外就是学会使用google,不管是初学阶段还是以后，都会遇到各种奇奇怪怪的问题，这时候google一下你就发现，绝大部分问题别人都遇到过并且已经解决了。

##手册目录
1. ROOT安装 
2. 必备技能包
    1. Histogram
    2. TCanvas 
    3. TTree
3. 其他常用类

