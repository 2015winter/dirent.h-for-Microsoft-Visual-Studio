dirent.h for Microsoft Visual Studio
====================================

在windows上使用的dirent接口，用于unix到windows的代码移植

项目地址为http://softagalleria.net/dirent.php
github上只是该项目的一个副本。
感谢Toni Ronkko提供此代码让我便于调试。

以下为官网介绍的译文，敬请参考：

介绍
    Dirent是一个可以列出文件和文件夹的程序开发接口。Dirent接口在Unix系统非常
通用，但是没有windows上的编译器提供这个接口。特别是,Microsoft Visual Studio
缺乏dirent接口。
    所以，如果你在向windows平台移植软件，你可能发现你正在为windows平台API重写
代码，为了减少这项工作，我在Microsoft Visual Studio环境下编写了这个Dirent接口
。这个接口尝试去模仿UNIX平台上的Dirent接口，所以你可以在Unix和windows平台下都
使用熟悉的Unix平台下的结构体和函数接口，而不必为了某一个平台修改源代码。

更多内容请大家访问官网。
