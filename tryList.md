# 练手的小项目
> 原文出处：[有了这个列表，程序员不愁没练手的小项目][1]，自己练练，肯定写不完，只是作为一个选材池慢慢来，写完了的部分开源（标题链接）。（以#开头的可直接用playground写，删除了一些不适合iOS开发的项目）

## 文本操作
1. [x] **001. # [逆转字符串][2]**——输入一个字符串，将其逆转并输出。
1. [x] **002. # [拉丁猪文字游戏][3]**——这是一个英语语言游戏。基本上是将一个英语单词的第一个辅音音素的字母移动到词尾并且加上后缀-ay（譬如“banana”会变成“anana-bay。可以在维基百科上了解更多内容。
1. [x] **003. # [统计元音字母][4]**——输入一个字符串，统计处其中元音字母的数量。更复杂点的话统记每个元音字母的数量。
1. [x] **004. # [判断是否为回文][5]**——判断用户输入的字符串是否为回文。回文是指正反拼写形式都是一样的词，如“racecar”。
1. [x] **005. # [统计字符串中的单词数目][6]**——统计字符串中单词的数目，更复杂的话从一个文本找出字符串并生成单词数目统计结果。
1. [ ] **006. 文本编辑器**——记事本类型的应用，可以打开、编辑保存文本文档。可以增加单词高亮和其它的一些特性。
1. [ ] **007. # RSS源创建器**——可以从其它来源读取文本并将其以RSS或者Atom的格式发布出去。
1. [ ] **008. 实时股价**——可以查询股票当前价格。用户可以设定数据刷新频率，程序会用绿色和红色的箭头画股价走势。
1. [ ] **009. 密码短信**——可以将数据加密解密，并能将其发送给朋友。
1. [ ] **010. 帮你挑礼物**——输入一堆你可能会送的礼物，当有人过生日时，该程序会随机选择一样礼物。也可以加一个额外功能，可以告知哪里可以弄到这个礼物。
1. [ ] **011. # CD-Key生成器**——利用某种算法生成一个唯一的key。软件开发者可以用它来作为软件的激活器。
1. [ ] **012. # 正则表达式查询工具**——用户可以输入一段文本，在另外控件里输入一个正则表达式。运行以后会返回匹配的内容或者正则表达式中的错误。

## 网络
1. [ ] **013. FTP工具**——与远程网络服务器交互文件。
1. [ ] **014. 原子钟校时**——从网上同步原子钟时间。全世界有很多原子钟，可以把它们都列出来。
1. [ ] **015. 聊天应用（IRC或者MSN风格的）**——像IRC那样的聊天软件或者MSN那样的实时聊天软件。更复杂一点的话，可以为聊天制定一套你自己的传输协议。
1. [ ] **016. # 获取当前天气**——获取某地区当前的天气情况。
1. [ ] **017. P2P文件共享应用**——像LimeWire、FrostWire、Bearshare或者torrect风格的应用。
1. [ ] **018. 端口扫描器**——输入某个ip地址和端口区间，程序会逐个尝试区间内的端口，如果能成功连接的话就将该端口标记为open。
1. [ ] **019. 邮件工具（POP3/IMAP）**——用户输入一些账号信息，包括服务器、ip、协议类型（POP或者IMAP），应用每隔一段时间就会检查下该账号下的邮箱。
1. [ ] **020. # IP注册查询**——输入ip地址，查询该ip是在哪注册的。
1. [ ] **021. whois查询工具**——输入一个ip或者主机地址，通过whois查询并将结果返回。
1. [ ] **022. # 邮编查询**——输入邮编，返回使用该邮编的地址名称。
1. [ ] **023. 远程登入**——远程登入桌面类型的应用，可以查看和控制远程电脑（假如你已经获得权限）。可能需要你自己的网络和两台电脑来进行测试。
1. [ ] **024. 网站定时检查器**——每隔一段时间或者在预定的时间尝试连接某个网站或者服务器，来检查它是否可以连上，如果连不上了会通过邮件或者桌面通知来告知你。
1. [ ] **025. 网络蜘蛛**——一个可以自动执行网页上各种任务的程序，任务包括网站检查、页面抓取、数据摘要以及网络邮务。

## 类
1. [ ] **026. 产品库存管理**——创建一个管理产品库存的应用。建立一个产品类，包含价格、id、库存数量。然后建立一个库存类，有各种产品并能计算库存的总价值。
1. [ ] **027. 电影商店**——管理录像带租借，记录借出时间、到期时间、逾期费用。复杂一点可以生成逾期用户的账号报告。
1. [ ] **028. 航空/酒店预订**——创建一套预订航班或酒店的预订系统。不同的航班座位和酒店房间收费不一样。譬如头等舱要比经济舱贵。带阁楼的套间要更贵些。记录下何时有空房可供预订。
1. [ ] **029. 学生成绩管理器**——记录一个班级的学生（创建一个student类，记录他们的名字、平均分和考试分数）和他们的成绩等级。根据学生的测验和作业的分数计算出平均分和成绩等级。复杂一点可以将数据画在贝尔曲线上。
1. [ ] **030. 银行账户管家**——创建一个名为“Account”的抽象类，有三个为checkingAccount”、“SavingsAccount”和“BusinessAccount”的子类。通过类似ATM的程序来管理这些账户的借贷。
1. [ ] **031. 馆藏目录**——创建一个图书类，记录书名、页数、国际标准书号、是否借出。用它来管理各种书籍，允许用户进行借出和归还操作。复杂一点的话，可以生成逾期图书和逾期费用的报告。也可以进行预约操作。

## 线程处理
1. [ ] **032. 下载进度条**——创建一个表示下载进度的进度条。进度条由独立的线程操作，通过委托来和主机进行通讯。
1. [ ] **033. 下载管理器**——允许程序同时下载数个文件，每个都用单独的线程进行背景下载。主线程会关注下载进度并且在下载完成后通知用户。
1. [ ] **034. 聊天软件（远程聊天）**——做一个聊天软件，允许你通过ip直接连接到另一台电脑，也允许你的“服务器”程序处理多个请求连接。
1. [ ] **035. 批量缩略图生成器**——在进行图片转换的处理时会需要很多时间，尤其是图片很大时。做一个图片处理程序，让你在做其它事的时候在后台线程里将数百张图片转换成某个大小的图片。复杂一点的话可以用一个线程来缩放，用另一个线程来为缩略图重命名。

## Web应用
1. [ ] **036. 文件下载器**——该程序可以从网页上下载各种资源，包括视频和其它文件。用于有很多下载链接的网页。
1. [ ] **037. 远程登录**——创建一个远程登录的应用，可以通过网络登录服务器并能执行一些基本命令。
1. [ ] **038. 在线白板**——做一个在线白板程序，你和朋友们可以一起在白板上进行一些操作，画图、写字等等。
1. [ ] **039. 带宽监视器**——这个小工具可以记录你已经在网上上传和下载多少数据流量了。可以试着做份报告或者图表来展示各时段的使用情况。
1. [ ] **040. 书签搜集管理器**——该程序可以让用户上传书签并将它们排序，去掉重复的，并能生成书签文件以供Firefox/IE/Safari等使用。复杂一点的话可以试着将书签整理进不同的文件夹。
1. [ ] **041. 密码保险箱**——用来记录各种密码，并且将它们加密，这样别人就看不到了。
1. [ ] **042. 电子卡片生成器**——可以让用户制作自己的电子卡片并发送给其他人。可以使用flash也可以不用。可以使用图片库，也可以加上深刻的格言警句。
1. [ ] **043. 验证码生成器**——应该在登录时见过有数字有字母的验证码图片吧？这可以防止自动登录和垃圾广告。试着自己做一个，如果使用PHP的话，看下GD的图片函数。

## 文件
1. [ ] **044. 试卷生成器**——该程序可以从文件中随机挑选出不同的题目生成一份试卷。每4份试卷可以不一样，通过读取答案来给打分。
1. [ ] **045. 快速启动**——该工具可以添加各个程序的小图标，点击小图标就可以运行程序。和Windows的快速启动类似。
1. [ ] **046. 文件管理器**——做一个文件管理器，要加些新特性，更佳的搜索功能、新图标、新外观。
1. [ ] **047. 文件记录排序工具**——从文件中读取记录，将其排序并写回文件中。允许用户选择排序风格以及排序关键字。
1. [ ] **048. 生成财务交易文件并且算出平均值**——将财务交易读进文件，按照账户分类、算出各项目的总量或平均值、理清各账户的借贷数据。
1. [ ] **049. Zip文件生成器**——用户输入不同文件夹的文件，也许还包括其他电脑中的文件，然后程序将这些文件打包成zip文件。复杂一点的话，打包时对这些文件进行压缩。
1. [ ] **050. PDF生成器**——从txt、html或其它文件中读取数据生成PDF文件。可以做成一个网页服务，用户上传文件，返回一个pdf版本。
1. [ ] **051. 批量文件命名器**——程序批量处理一些文件，将根据用户提供的过滤器为它们重命名。譬如用户输入的过滤器为myimage###.jpg，那么会生成至少包含3位数的文件名，譬如myimage001.jpg、myimage145.jpg，甚至是myimage1987.jpg，因为1987也满足了至少包含3位数的条件。
1. [ ] **052. 文件复制工具**——该工具可以批量处理文件复制和备份操作。

## 数据库
1. [ ] **053. SQL查询分析器**——该工具可以让用户输入一条查询命令，让其运行于本地数据库中。尽量让它运行得更高效。
1. [ ] **054. 远程SQL工具**——该工具能让你通过网络在远程服务器上执行查询操作。它能6接收远程主机地址、验证用户名和密码、执行查询并返回结果。
1. [ ] **055. 卡片整理器**——创建一个在线应用，用来记录搜集到的卡片。可以让用户输入整套卡片，查看哪些已经有了，哪些还需要搜集。要增加复杂度的话，还可以让用户知道还差多少可以完成，或者已经收集卡片的价值。
1. [ ] **056. 报告生成器**——该工具可以根据数据库中的表格生成一份报告。譬如根据订单表格生成销售报告。
1. [ ] **057. 数据库备份脚本制作器**——该程序可以读取数据库的对象、关系、记录和步骤，生成一个sql文件，该文件可以导入另一个数据库或者作为备份文件。
1. [ ] **058. 备忘录**——该程序可以让用户设置一个日期和某个事件的时间、事件备注并将它们放到日历上。用户可以查看日历、搜索特定的事件。复杂一点的话，可以让用户设置重复发生的事件，譬如每天、每周、每月、每年等等。
1. [ ] **059. 预算记录器**——该程序可以记录家庭预算。用户可以添加支出、收入，计算一段时间内的收入和支出。复杂一点的话，让用户指定一个时间段，显示该时间段内的家庭收支情况。
1. [ ] **060. 电视节目记录器**——你是否有不想错过的电视节目？但没有录像机或者想之后能找到该电视节目然后录下来，那么可以做个程序寻找各种在线电视导航网站，记录下电视节目名称、播放时间、播放频道，存在数据库中。数据库或者网站到时就会发邮件提醒你，节目就快在某个频道开始了。
1. [ ] **061. 旅行计划系统**——该系统可以让用户管理旅行路线，记录下航班和酒店安排、感兴趣的地方、预算和时间表。
1. [ ] **062. 实体关系图生成器**——该程序可以让用户整合实体关系图，并将其保存起来，也可以用它来生成一些基础SQL语句。

## 图像和多媒体
1. [ ] **063. 幻灯片**——做一个以幻灯片形式显示各种图片的程序。为了增加难度可以做些额外的效果，譬如渐进检出、星型擦除、窗口渐隐。
1. [ ] **064. 思维导图**——允许用户记录下各种构思并且快速地进行头脑风暴将这些构思整合到一张思维导图中。越快越好，因此要让用户能迅速地写下构思，然后将其拖到可视的导图中去，将构思之间的关系展现出来。
1. [ ] **065. 导入图片并存成灰度图**——该工具将图片上的彩色除尽并保存。可以增加对比度调整、色化等额外功能以增加复杂度。
1. [ ] **066. 在线流媒体视频**——试着自己做一个在线流媒体视频播放器。
1. [ ] **067. MP3播放器（以及其他格式的音乐播放器）**——该小程序用来播放你最爱的音乐文件。复杂一点的话看看能否加个播放列表功能和均衡器。
1. [ ] **068. 批量图片处理**——该程序可以将一个文件夹内的图片进行统一的处理，譬如降低图片色调、转换格式或者修改文件属性。还可以尝试给图片增加标签。
1. [ ] **069. 交通信号灯**——试着做一个交通信号灯并且把它放到可以互动的场景中。不要让汽车闯红灯或者撞到其它车。
1. [ ] **070. 签名生成器**——是否在网上见过有人的留言后面有条生成的签名？试着做个程序让用户可以指定背景、文字、颜色和对齐方式来定制一个签名档。
1. [ ] **071. 水印**——你是否想保护你图片的版权？在图片上加上标志或者文字，这样别人就不能轻易地从你网站上盗图了。做一个程序来给你的图片加上水印吧。

## 游戏
1. [ ] **072. 海龟图**——创建一个20\*20的格子，用命令让一只海龟在格子上画线。可以前进、左转、右转，拿起或放下笔等等。复杂一点的话，允许程序从文件中读取命令列表。可以在网上了解到更多关于“海龟图”的信息。
1. [ ] **073. 战船**——创建两块游戏面板，玩家各占一边，在上面放置一些战船，玩家看不到对方的面板。每艘船都占几个格子，玩家轮流攻击某个格子，如果格子上有船，那就命中目标，否则就是未命中。当一艘船所占的所有格子都被攻击命中了，那么船就被击沉。谁先将对方战船全部击沉就获胜。
1. [ ] **074. 象棋跳棋**——象棋或者跳棋游戏。可以试着做成可以联网玩，用图形用户界面来实现悔棋、保存走棋过程并且可以回放。
1. [ ] **075. 刽子手**——从文件中随机选择一个单词，让玩家猜单词中的字母。旁边是一幅隐藏的行绞刑的画，猜错一个单词，画就显示出一部分。画全部显示出来时还没能猜全的话玩家就输了。
1. [ ] **076. 填字游戏**——创建一个填字游戏，并为每个词提供一个提示信息，让玩家填上所有正确的单词。
1. [ ] **077. 青蛙跳**——让青蛙跳过河或者马路，过河的话要跳在顺流而下速度各异的木头或者睡莲叶子上，过马路的话要避开速度各异的车子。

[1]:	http://blog.jobbole.com/49762/
[2]:	https://github.com/conanwhf/swiftplayground/blob/master/Exercise_Demo.playground/Pages/001-005.xcplaygroundpage/Contents.swift
[3]:	https://github.com/conanwhf/swiftplayground/blob/master/Exercise_Demo.playground/Pages/001-005.xcplaygroundpage/Contents.swift
[4]:	https://github.com/conanwhf/swiftplayground/blob/master/Exercise_Demo.playground/Pages/001-005.xcplaygroundpage/Contents.swift
[5]:	https://github.com/conanwhf/swiftplayground/blob/master/Exercise_Demo.playground/Pages/001-005.xcplaygroundpage/Contents.swift
[6]:	https://github.com/conanwhf/swiftplayground/blob/master/Exercise_Demo.playground/Pages/001-005.xcplaygroundpage/Contents.swift