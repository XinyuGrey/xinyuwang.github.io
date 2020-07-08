1. 前言
-------

5G技术时代的到来，无疑会带来许多行业的变革。在数据科学领域，Rstudio公司在推出基于服务器的Rstudio
server之后，又推出了基于网页的Rstudio
cloud（目前仍处于测试状态）。本文将首先介绍Rstudio
cloud的功能、特点和优缺点，其次介绍Rstudio cloud与Rstudio server的区别。

2. Rstudio cloud的功能与特点
----------------------------

Rstudio cloud的[官方介绍](https://rstudio.cloud/)如下：

> THE MISSION：We created RStudio Cloud to make it easy for
> professionals, hobbyists, trainers, teachers and students to do,
> share, teach and learn data science.

Rstudio
cloud的任务就是令其使用者可以轻松地进行、共享、教授和学习数据科学。

> INSTANT ANALYSIS：Create your analyses using RStudio directly from
> your browser - there is no software to install and nothing to
> configure on your computer.

Rstudio
cloud的功能之一：即时分析，无需安装任何软件直接从浏览器使用RStudio创建分析，也无需在计算机上进行任何配置。

> PAINLESS SHARING：Share your projects - and access those of others -
> without worrying about data transfer or package installation. Each
> project defines its own environment, and RStudio Cloud automatically
> reproduces that environment whenever anyone accesses the project.

Rstudio
cloud的功能之二：轻松分享，共享使用者的项目并访问其他人的项目，无需担心不同使用者之间数据传输或软件包安装的差异。每个项目都定义了自己的环境，只要有人访问该项目，RStudio
Cloud就会自动复制该环境。

> PRIVATE COLLABORATION：It’s easy to share your analyses with the world
> - but it’s also simple to collaborate with a select group in a private
> space. Spaces let you control who can create and interact with
> projects - and via roles, give you fine grained control over what each
> user can do.

Rstudio
cloud的功能之三：私人合作，可轻松将使用者的分析成果与全世界分享，并且与私人空间中的特定小组协作也很容易。使用空格键可以控制哪些人可以创建项目并与之交互，并且通过角色对每个用户的操作进行精细的控制。

> LEARNeR：We also provide many learning materials: interactive
> tutorials covering the basics of data science, cheatsheets for working
> with popular R packages, and a guide that covers the basics of using
> RStudio Cloud.

Rstudio
cloud的功能之四：为学习者提供许多学习材料，涵盖数据科学基础知识的交互式教程，使用流行的R软件包的cheatsheets，以及涵盖使用RStudio
Cloud的基础知识的指南。

简单的来说，Rstudio
cloud就是网页版的Rstudio，并且具有分享、协同合作和学习的功能。

3. Rstudio cloud的使用方法
--------------------------

本文借鉴[如何使用Rstudio
cloud](https://www.jianshu.com/p/34374cad9cb3)，简单介绍Rstudio
cloud的使用方法。

RStudio
Cloud是RStudio的网页版，通过注册登录，可以在不同电脑上对自己的云端RStudio数据进行操作，还可以使用Google或github账号登录。网址为：
<a href="https://rstudio.cloud" class="uri">https://rstudio.cloud</a>

1.  登录界面

![](C:/Users/Xinyu/Desktop/plot/初始页面.png)

![](C:/Users/Xinyu/Desktop/plot/登录页面.png)

1.  创建project

project是RStudio
Cloud的基本工作单位，其储存R代码、R包及数据，并且与其他project是分离的。除了桌面版Rstudio的基本功能外，它还额外具有访问和共享的功能。点击**New
Project**创建project。

![](C:/Users/Xinyu/Desktop/plot/project页面.png)

打开Project，RStudio Cloud与桌面版RStudio界面完全一致。

![](C:/Users/Xinyu/Desktop/plot/projec页面.png)

1.  通过upload和export，可以实现数据上传和导出。

![](C:/Users/Xinyu/Desktop/plot/上传文件.png)

![](C:/Users/Xinyu/Desktop/plot/导出文件.png)

1.  分享和copy

默认情况下，你创建的任何project都只能自己访问。要与他人共享一个项目，单击项目设置按钮(右上角的齿轮)，将“谁可以查看该项目”更改为“所有人”。

![](C:/Users/Xinyu/Desktop/plot/分享页面.png)

然后在浏览器中复制项目地址并发送链接。注意，任何有链接的用户都可以查看你的项目！

![](C:/Users/Xinyu/Desktop/plot/连接页面.png)

当你访问由其他人创建的项目时，RStudio
Cloud会自动创建原始项目的临时副本。你可以使用它并对其进行编辑，但是任何更改都不会反映在原始版本中。如果你想保留所做的更改，只需按下save
a Permanent copy按钮为自己保存一个项目的副本。

![](C:/Users/Xinyu/Desktop/plot/保存project.png)

1.  手机查看与操作

电脑上的网页如下：

![](C:/Users/Xinyu/Desktop/plot/手机-电脑页面.png)

点击上文分享部分的连接，手机上的页面如下（也需要登录自己的账号）：

![](C:/Users/Xinyu/Desktop/plot/手机页面.jpg)

1.  其他功能

此外，RStudio Cloud还提供多个R包的cheat
sheet,如关联R和Python之间的reticulate包、处理因子类型数据的forcats包等。

![](C:/Users/Xinyu/Desktop/plot/其他功能.png)

点击**Feedback and Questions** 可直接跳转到[Rstudio
cloud社区](https://community.rstudio.com/c/rstudio-cloud?_ga=2.87810384.972133968.1594126861-2069470579.1594126861)

![](C:/Users/Xinyu/Desktop/plot/community.png)

点击**Primers**可在网页学习Rstudio提供的data science课程
![](C:/Users/Xinyu/Desktop/plot/primer.png)

**Guide**和**What’s New**分别提供Rstudio cloud的使用指引和最新消息。

1.  何时发布呢？！！！

Rstudio
cloud现在处于测试阶段，但计划于`2020年8月3日`投入使用。将继续添加重要功能并提高性能、可靠性和可用性。小伙伴们不要错过哦！

4. Rstudio cloud的优缺点
------------------------

Rstudio cloud作为一款新产品必然有它的优势。

-   优点
    -   免费：开源真香！
    -   不吃电脑配置，只吃网速
    -   随时同步：由于是云端软件，所以任何可以联网的设备就能登录账号同步自己的RStudio!
    -   安装包、下载数据无压力
    -   分享与共享：单击项目设置按钮，将“谁可以查看该项目”更改为“所有人”，就可以将整个项目分享给其他人，为团队协作提供便利！
-   缺点
    -   注册、排队运行、保存费时
    -   连接不到网络无法使用！！
    -   网速不给力，气死人（5G时代这不是问题）
    -   

5. Rstudio cloud与Rstudio server的区别
--------------------------------------

RStudio
Server是一个Linux服务器应用程序，它为运行在服务器上的R版本提供基于Web浏览器的界面。
您可能希望RStudio服务器执行以下操作：访问更大的CPU和内存占用量；更有效地利用计算资源；集中控制对数据的访问；确保使用的R软件包版本是标准化的。

Rstudio cloud与Rstudio server的区别在于Rstudio
server是需要搭建在服务器上的，所以同样也吃服务器配置，并且自行配置服务器也会比较繁琐，而
Rstudio
cloud不需要，只需要创建一个账号就可以在网页上流利的进行数据科学工作。

Rstudio
server的安装教程可以参考：[服务器上安装Rstudio-server](https://www.jianshu.com/p/d9e654b10829)
