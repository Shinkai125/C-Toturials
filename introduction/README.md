# C语言简介

## C语言来历

对与网络上的19XX年，哪个实验室，哪个人，做了什么之类的资料太多了，所以我这里不赘述，有兴趣的可以看看[百度百科里C语言的来历](http://baike.baidu.com/view/1219.htm)。我在这呢，只简单地提几句需要注意的地方：

1. C语言之父是<font color=red>丹尼斯·里奇</font>，不是谭浩强；
2. C语言是在B语言基础之上设计的，但这<font color=red>并不意味着</font>B语言是在A语言的基础上设计的；
3. B语言与C语言名字的来历与字母表顺序无关，是因为他们是以BCPL语言作为基础的，B语言取了第一个字母，C语言取了第二个字母；
4. A语言的命名由来是：世界上第一位程序媛的名字叫Ada。

## 特点与优势

关于C语言到底是高级语言还是低级语言，从来都没有一个定论。认同者比较多的说法是：C语言是高级语言中的低级语言，低级语言中的高级语言。

特点：

1. 语言简洁；
2. 运算符与数据类型丰富（32个关键字，9种控制语句）；
3. 执行效率高（因为偏底层，这也是优势）；
4. 程序可移植性好（可移植性：仅对程序做小的修改，或不做修改，就能在其他平台上运行）；

因为C语言直接操作的时内存地址，所以在安全性方面有一定缺陷。