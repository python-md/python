# python基础认识
## 一、什么是python?
    * 相信很多小白,或者刚接触python的人会这样问。Python是一种面向对象的解释型计算机程序设计语言,由荷兰人吉多·范罗苏姆于1989年发明,第一个公开发行版发行于1991年。Python语法简洁清晰,特色之一是强制用空白符作为语句缩进。Python具有丰富且强大的第三方库,被称之为胶水语言。
## 二、python发展史
    1. Python的创始人为吉多·范罗苏姆1989年的圣诞节期间,吉多·范罗苏姆为了在阿姆斯特丹打发时间,决心开发一个新的脚本解释程序,作为ABC语言的一种继承。之所以选中Python作为程序的名字,是因为他是BBC电视剧——蒙提·派森的飞行马戏团(Monty Python's Flying Circus)的爱好者。

    2. 1991年,第一个Python编译器诞生。它是用C语言实现的,并能够调用C语言的库文件。从一出生,Python已经具有了:类,函数,异常处理,包含表和词典在内的核心数据类型,以及模块为基础的拓展系统。最初的Python完全由Guido本人开发。Python得到Guido同事的欢迎。他们迅速的反馈使用意见,并参与到Python的改进。Guido和一些同事构成Python的核心团队。随后,Python拓展到研究所之外。Python将许多机器层面上的细节隐藏,交给编译器处理,并凸显出逻辑层面的编程思考。

    3. Python程序员可以花更多的时间用于思考程序的逻辑,而不是具体的实现细节,这一特征吸引了广大的程序员。Python开始流行。

    4. Python2.0于2000年10月16日发布,增加了实现完整的垃圾回收,并且支持Unicode。

    5. Python3.0于2008年12月3日发布,此版不完全兼容之前的Python源代码。不过,很多新特性后来也被移植到旧的Python2.6/2.7版本,目前最新版本是 Python 3.6.3
## 三、python语言能做什么工作？
1. Web应用开发:
    * Python开发web后台以开发快,周期短闻名,有三大著名web框架django,flask,Tronado,许多大型网站就是用Python开发的,例如YouTube、Instagram,还有国内的豆瓣。

2. 爬虫开发:
    * Python用requests,scrapy等库开发爬虫是一件让人很愉快的事情。

3. 自动化运维开发:
    * 大多数Linux发行版以及NetBSD、OpenBSD和MacOSX都集成了Python,可以在终端下直接运行Python。Python编写的系统管理脚本在可读性、性能、代码重用度、扩展性几方面都优于普通的shell脚本

4. 科学计算:
    * NumPy,SciPy,Matplotlib可以让Python程序员编写科学计算程序。

5. 桌面软件:
    * PyQt、PySide、wxPython、PyGTK是Python快速开发桌面应用程序的利器。

## 四、python的优缺点
1. 优点:
    * 简单,易学:
        * Python是一种代表简单主义思想的语言。阅读一个良好的Python程序就感觉像是在读英语一样,尽管这个英语的要求非常严格!Python的这种伪代码本质是它最大的优点之一。它使你能够专注于解决问题而不是去搞明白语言本身,语法相对简单。

    * 免费、开源:
        * Python 开源,开发者可以自由的下下载,阅读,甚至是修改python源码。

    * 可以移植:
        * 由于Python是开源的,它已经被移植到了大多数平台下面,例如:Windows、MacOS、Linux、Andor有7id、iOS等等。

    * 解释性:
        * 大多数计算机编程语言都是编译型的,在运行之前需要将源码编译为操作系统可以执行的二进制格式(0110格式的),这样大型项目编译过程非常消耗时间,而Python语言写的程序不需要编译成二进制代码。你可以直接从源代码运行程序。在计算机内部,Python解释器把源代码转换成称为字节码的中间形式,然后再把它翻译成计算机使用的机器语言并运行。

    * 面向对象:
        * Python既支持面向过程,又支持面向对象,这样编程就更加灵活。

    * 丰富的第三方库:
        * Python具有本身有丰富而且强大的库,而且由于Python的开源特性,第三方库也非常多,例如:在web开发有django,flask,Tornado、爬虫scrapy、科学计算nupy,pandas等等。
2. 缺点:
    * 运行速度慢:
        * Python是解释型语言,所有它的速度会比,C、C++慢一些,但是不影响使用。由于,现在的硬件配置都非常高,基本上没有影响,除非是一些实时性比较强的程序可能会受到一些影响,但是也有解决办法,可以嵌入C程序。

    * 国内市场较小:
        * 目前来说国内市场相比其他热门语言来说还是比较小,但是很多公司已经开始使用python,发展势头很足,其实并不算缺点。
    * 强制的缩进:
        * Python有非常严格的缩进语法,只要缩进错误程序立马崩溃。

## 五、第一个python程序
1. 打开终端,输入python3进入到python3版本的解释器。如果输入python那么进入的是python2版本的python解释器。

* ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/1.png)

2. 在编辑器中输入print（“hello world”）；
    * 输入 print("hello world")
    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/2.png)
    * 输出hello world
    * ![Image text](https://github.com/python-yyb/python/raw/master/3.png)

3. 这样写的代码只能运行一次,那我怎样才能保存成文件重复运行呢?创建一个以.py结尾的文件,在文件中写入 print('hello world')执行python3 hello.py 可以看到hello world 输入。
    * vim.py创建一个yyb.py文件

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/4.png)

    * 进入文件编辑模式后，按键盘的i键进入插入模式

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/5.png)

    * 输入 print（'hello world'）

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/6.png)

    * 然后按键盘esc退出插入模式，然后按shift+；，输入wq保存退出

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/7.png)

    * 最后执行文件，终端输入:python3 yyb.py

4. 每次执行都要输入python3,哎,好麻烦啊,怎么样能简化下呢?
在python代码第一行加入 #!/usr/bin/env python3 指定解析器

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/8.png)

    * 给hello.py文件加上执行权限

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/9.png)

    * 执行hello.py文件 用 ./hello.py 方式执行,这样就可以省去输入python3啦。

## 六、python程序的注释
1. python注释
    1. 为什么要有注释
        * 注释可以起到一个备注的作用,这个方法函数,变量到底是干嘛用的,如果没有注释时间长了即使是自己可能都不知道这代码到底是干嘛用的。所以注释起到的作用就是方便自己查看写过的代码,别人来接手你的代码能看懂
        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/10.png)

        * 没有注释的代码
        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/11.png) 

    2. 单行注释，我们使用#

        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/12.png)

    3. 多行注释，使用三个单引号'''内容''' 也可以使用三个双引号"""内容"""

        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/13.png)

    4. 特殊注释:Python中有两句特殊的注释,在py文件首行 #!/usr/bin/env python3 ; # -*- coding=utf-8 -*-这两句注释分别指的是指定python解析器的路径,指定编码格式,只能写在py文件最前面。

        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/特殊注释.png)

## 七、集成开发环境Pycharm
1. Pycharm是什么?
    * 适用于专业开发人员的 Python IDE。
    * 提高代码质量
    * 编写整洁和可维护的代码,而IDE可以帮助您通过PEP8检查,测试帮助,智能重构和一系列检查来保持质量。
    * 提供你所需要PyCharm是程序员为程序员设计的,它提供了所有你需要的有效的Python开发工具。
    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/pycharm功能.png)

2. Pycharm下载地址
    * 官网地址:http://www.jetbrains.com/pycharm/?fromMenu
3. 安装：进入bin文件夹，右键点击在终端中显示，输入 sudo sh pycharm.sh
4. 新建项目
    * file->New project->pure python->create
5. Pycharm 字体设置
    * file->settings->Editor->Colors&Fonts->Font-> Size 设置为18,Console Font Size 设置为18      
6.  新建.py文件
## 八、 变量和数据类型
1. 变量
    * 什么是变量？
        * 变量是程序中用来存储数据的东西。在程序运行中有些数据需要存储下来使用,那么这个时候就使用到了变量。
        * 比如程序中两个数字的相加,我们得先找两个变量来保存这两个数字:变量只是保留内存位置来存储值。这意味着当你创建一个变量时,你在内存中要保留一些空间。那应该保留多大呢?
        * 其实Python是根据变量的数据类型,解释器分配内存并决定保留内存存储内容。python是一个门弱类型的语言,赋值变量时不需要指定类型。给这个变量赋值什么类型,这个变量就是什么类型。
        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/变量.png)
2. 数据类型
    * Python有五种标准数据类型
        * 数字(num):
            * 其中数字类型包括:
                * int(有符号整数)
                * long (长整形)
                * float (浮点型)
                * complex (复数 )
        * 字符串(str):
        * 字典(dict):
        * 元祖(Tuple):
        * 列表(list):
    * 当然python也有布尔值  true false
3. 我们知道有数据类型有这么多,怎么样才能知道变量时一个什么类型呢?
    * Python提供了type方法查看变量的类型。
        * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/type.png)

4. 变量的命名规则
    * 必须以字母(a -z，A -Z)或下划线(_)开头
    * 其他字符可以是字母，数字或_ 
    * 区分大小写 
    * python关键字不能用作变量名

5. 命名规范
    * 见名知意，尽量使用有语义的单词命名。如使用password用作密码，username用户名
    * 小驼峰式命名法:第一个单词首字母小写其他单词首字母大写，如uaerNane
    * 大驼峰式命名法:全部单词首字母都用大写，如UserName
    * 下划线命名法:每个单词用_下划线连接，如user_name

6. python关键字
    * 查看python关键字可以在解释器中导入keyword模块查看

## 九、python基本运算符
1. 算术运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/算术运算符.png)

2. 比较运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/比较运算符.png)

3. 逻辑运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/逻辑运算符.png)

4. 赋值运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/赋值运算符.png)
    
5. 位运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/位运算符.png)

6. 成员运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/成员运算符.png)

7. 身份运算符

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/身份运算符.png)

8. 运算符的优先级

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/运算符优先级.png)

## 十、 python输出和输入
1. 输出
    * 变量内容的输出:print('helloworld')
2. 格式化输出 
    * 来看下下面这三句代码的输出有什么特点，好像只有一个名字不同。‘我来自一班’三个人都是一致的， 有没有办法简化下代码呢?要简化，那么我们就用到了字符串格式化。 

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/14.png)

3. 什么是字符串格式化呢?
    * python有一个简单的字符串格式化方法，使用%做占位符。%后面跟的是变量的类型

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/15.png)

4. 知道什么是格式化输出后，我们来简化下上面的代码

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/16.png)

5. 常用的格式化符号，其中最常用的%s,%d,%f

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/17.png)

6. python 输入
    * python中提供了input方法来获取键盘输入

    * ![Image text](https://raw.githubusercontent.com/python-yyb/python/master/18.png) 

    * 注意:input接收的键盘输入结果都是str类型的，如果接收数字类型需要将将str转成int




