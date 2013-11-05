Lee
===
学过C++，从事C# 好还是Java好呢 ？--摘自csdn (2007-03-10 00:19:54)转载▼
* sample 1: 
-----
    学过C++，从事C# 好还是Java好呢？
三者的语言方面都学习过，做过C++的东西，主要是.net下VC
后面两者也实践过一些，但很皮毛，
如果现在选择C#和Java，哪一个更合适呢？
感觉从事Java和C# 各有利弊，请大家提提意见。
* sample2:
    我是非常喜欢C++的,但毕业后的单位只用C#和Java,分别在两个部门,很想找个C++的单位,但和这个单位毁约不一定能找到一个好的、用C++的单位，
也知道Java和C#这两个阵营都很大，内容都很多，但问题是现在这个单位要在培训之后定是参加C# 的部门还是Java的，因为不想一直做底层的程序员，希望最终能搞架构，所以就问问大家了，目的就是想知道，为达到最终目的，Java和C#哪一个更合适。
* sample3:
    我们这学期开始学JAVA了
在第一节课上，老师说JAVA的优势在于网络？？
还有JAVA的速度比C/c++要慢3-4倍……
我挺不理解的……那JAVA好在哪里
我们已经学过c++了，有一些人说JAVA如何如何的好，我挺困惑的，在性能上比C/c++慢这么多，而且.Net对网络的支持也很好啊
请各位给解释一下
==========================
篇幅有限，我就不一一列举了。
首先，我要说的就是语言本身没有高低贵贱之分，所有的语言存在都有他存在的意义。
java，跨平台，由于虚拟机的存在，java的速度肯定无法和C/C++相比，但是也不像某些人说的那么夸张。
java，Java有一个特别的“垃圾收集器，它会自动释放由那些闲置对象占据的内存，以便能由新对象使用，这样可以有效防止由于程序员忘记释放内存造成的“内存溢出”，但是肯定也是牺牲性能为代价
java，数组。由于系统自动进行范围检查，所以必然要付出一些代价：针对每个数组，以及在运行期间对索引的校验，都会造成少量的内存开销。但由此换回的是更高的安全性，以及更高的工作效率。为此付出少许代价是值得的。
。。。。。。
在这里也就不仔细比较java与c/c++的性能优劣了。
java是一种静态语言，它的开发缺少灵活性。
ruby on rails的开发web的效率号称是java的10倍，但是在企业级应用上来说，java本身还是首选语言。强大的API，丰富的第三方软件支持，framework也在激烈的竞争中不断的优化，source容易让初进入项目的人读懂，门槛也比较低。
记得在《程序员2006年合订本》有个“华山论剑”的记录了各种语言的优点的优势，有兴趣的可以看看。
我说这么多的意思就是，希望初学者不要盲目的去赶时髦，一味的追求新技术。
今天学java，然后c++,然后.net，还雄心勃勃的说：我要在短时间内精通“struts，hibinate，jsf，spring，applet”......
过了几天，发现现在公司或者论坛上看到现在流行JSF，又去研究JSF。
过了几天，又是ruby，python......
简直看花眼了。
所以要认定一门语言，认真打好基础。语言本身并不重要，重要的是设计思想。
无论是c++还是java还是其他的动态语言，就程序控制来说，无非就是顺序结构，循环结构，递归。
相比在上学的时候，我们学过c语言对这些基本的东西应该有所了解吧
我们所要学习的正是继承，重载，多态，封装等这些面向对象的精髓，需要具备的是把具体的事物抽象成具体的类的能力。
何时应该使用继承，何时因该使用抽象类，何时应该使用接口，各个类之间通过什么来联系，等等。

基础学好了，然后可以开始学习一些API之类的东西，这些东西不要去研究它，只要达到能用就可以了。要用的时候再去查找它的具体用法。
实际项目中，需要用到的framework，apserver，xml之类东西的时候，再去学习他。
比如，项目中用 java + struts + jsp ，那我就学习struts。
项目中用到JSF，我就学JSF，用道Applet，我就学Applet。
有人会说，这样的话，不是又变成什么都学，什么都不精通么？
最简单的说句，公司请你来，是请你来做事情的，还是请你来学习的呢？
刚开始的时候，你们不能决定公司到底用什么技术架构，你所能做的就是适应公司，这个时候，你要做一个有心人，主动地去看看项目是如何利用这些framework，如何利用这些中间件的。
现在的主流无非就是个MVC思想，几个项目下来，你肯定不具备这些架构的能力，但是只要你做个有心人，脚踏实地，你一定能有所收获的。
技术始终在变，惟有思想永恒（有点唯心主义了）。
=========================================================
有人问：
因为不想一直做底层的程序员，希望最终能搞架构，所以就问问大家了，目的就是想知道，为达到最终目的，Java和C#哪一个更合适。
既然语言本身没有高低贵贱之分，那么想要成为架构师，和你使用哪个语言似乎关系不大。
我觉得要成为一个合格的架构师，应该有这样的过程：
1.有足够的计算机基础，包括数据结构，数据库，C语言，汇编语言，软件工程思想
2.选择一门语言，通过这么语言学习一种思想，学习这种思想的精髓，无论是“面向对象”，还是现在的“SOA”。
3.参加实际的项目,这个时候不要过分的关注语言的本身，不要再在一些算法问题上钻牛角尖了，算法是你在1和2中应该去重点掌握的内容。
  我们要做的是结合项目实际，多想想为什么项目要用这样的架构，这种架构如何将db，中间件，开发语言有机的结合起来的，这样做有什么好处，这些中间件到底做了些什么事情。
  这样，通过不断的遇到问题，不断地思考，不断地解决，你的能力自然就提高了。
4 不想做底层的程序员，3这个步骤是漫长的而且是痛苦的。3经历的过程中，你可以开始看看“设计模式”，“UML”，“DB优化”这些高级的书籍了。
   有了面向对象的思想，和足够的项目经历，再加上你的努力，这些东西应该不难读懂。这个时候，你可以想想，我以前做的一些项目，如果让我来设计，我会如何去做。
5 如何把4学习的东西用到项目中去了。这个你不用担心，中国不缺民工，缺乏的就是具备一定能力的设计人才。只要你具备这样的能力，领导会看见，会给你机会的。
   只要你做的还可以的，你会得到更多的机会去设计。做的不好，那你就还需要锻炼，应为架构这东西很重要，搞得好，可以提高整个团队的效率，减少项目风险。搞不好，呵呵，自己考虑。
6 有了5的水平，相信你把握式样，跟客户交流应该没有什么问题了吧。
总之就是要脚踏实地，不要好高骛远，不要抱怨领导不给你机会，而是要时刻提醒自己“领导给我机会的时候，我真的准备好了么”？
