---
layout: page-fullwidth
subheadline:  ""
title:  "理工女故事 | 葛丽丝·霍普：与计算机交谈的海军准将 "
teaser: ""
breadcrumb: true
categories:
    - story
permalink: /blog-story/grace-hopper
header:
    image_fullwidth: "unsplash_brooklyn-bridge_header.jpg"
image:
    thumb: "unsplash_brooklyn-bridge_thumb.jpg"
    homepage: "grace-hopper.jpg"
---

![grace-hopper](/assets/img/grace-hopper.jpg)


<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
文 / 刘文舜
</strong></p>



![0.gif](/assets/img/grace-hopper/0.gif)

2013年12月9日，谷歌首页为我们描绘了这样一幅画面：一位女士坐在一架像是早期计算机的庞然大物面前，给出了两段近似于英文的指令： “从当前年份减去出生年份，得出年龄” “显示年龄”。庞然大物一阵灯光闪烁，随即吐出答案： “107”。

画面的女主人公正是在当日诞辰107周年的计算机科学家及美国海军准将葛丽丝 · 霍普（Grace Hopper）。在今天这个一切都智能化的世界，要求计算机推算年龄的命令看起来稀松平常，以至于我们早已忘记，无论看上去多么智能，它们也不过是由只会进行简单逻辑运算的电子元件组成的机器而已。那么，计算机是如何做到准确理解由自然语言组成的命令，并进行复杂操作的呢？

<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
世界上最早的程序员
</strong></p>



1906年出生于纽约的葛丽丝·霍普是家中的长女。从小，霍普就展现出了不同于常人的好奇心。七岁时，为了弄明白闹钟的工作原理，她拆掉了家中全部的七个闹钟。没有想到的是，小霍普的妈妈在发现这件事后并没有责骂她，只是规定一次实验只可以动用一个闹钟。原来，霍普的妈妈年轻时也曾对数学充满兴趣，无奈因为社会对女性的限制，她无法学到除了基础几何之外的任何数学知识。也正是因为这样的经历，她对小霍普的兴趣总是加以鼓励，并确保她的成长不会受到性别的限制。霍普的爸爸也尽其所能，让两个女儿和儿子获得一样的教育机会，这在20世纪初的其他家庭中是非常少见的。

在这样的家庭环境下，霍普成功地来到瓦萨学院（Vassar College）学习数学和物理，并在本科毕业后前往耶鲁大学继续深造。1934年，她在耶鲁大学取得数学博士学位，成为当时极少数能够获得这一学历的女性。完成学业的霍普选择回到瓦萨学院任教，直到第二次世界大战的爆发。

二战时的人手紧缺使得军队对女性及她们能担任的职务不再那么苛刻。在这样的大背景下，有超过20万名美国女性加入了军队专门为她们成立的各个分支。霍普志愿加入的美国海军后备军团（WAVES, Women Accepted for Volunteer Military Services）正是其中之一。霍普选择海军也有个人情感上的因素 —— 毕竟，霍普的曾祖父曾是一名参加过南北战争莫比尔湾战役的美国海军上将。当时，霍普的体重比军方规定的最轻标准还少了将近7公斤，但是因为战时人力短缺，军方最终还是批准了她的入伍请求。

1944年，从史密斯学院预备军学校毕业的葛丽丝 · 霍普因其出众的数学背景而被分配到美国船舶局位于哈佛大学的战时科研中心。此时正值军方在哈佛大学的马克一号（Mark I）计算机研究项目开启，葛丽丝 · 霍普自然而然地成为了这台电脑上的第一批编程人员。

马克一号被誉为“现代电脑时代的开端”，这个重达四吨的大家伙不仅是第一部万用型计算机，具有一开始运算便无须人为介入的全自动化循序控制能力，它的成功研发还在战时满足了像曼哈顿计划这种项目的大量计算需求。在这期间，葛丽丝 · 霍普和项目负责人霍华德 · 艾肯（Howard Aiken）共同发表了三篇论文，以阐述对于马克一号的研究成果。



![1.jpg](/assets/img/grace-hopper/1.jpg)

霍普在马克一号值班人员记录表上的签字

二战结束后，38岁的霍普曾申请转入海军的常规部队，但由于年龄因素，她的请求没能得到批准。在这之后，霍普放弃了瓦萨大学提供的教授席位，选择作为美国海军的一员留在哈佛计算科研中心。

任何一个程序员都会或早或晚碰到他的第一只“虫子”（bug，意指错误的程序），而这个术语的流行还得追溯到霍普在哈佛期间经历的一段趣事：

为了建造更快的计算工具以满足战时所需，哈佛马克二号项目于1944年开启。一日，马克二号因为不明原因停止运作，葛丽丝 · 霍普的部下经过仔细检查后，发现是一只飞蛾飞进继电器而造成了短路。有感于这个有趣的发现，他们便将飞蛾的残骸贴到了研发记录薄上，并标注为“第一只真正的虫子（bug）”。霍普也把这次危机的解除称做“除虫（debug）”。虽然这个词在更早之前已被用来指莫名的故障，但正因为这个故事，这一用法变得更加广为人知。从此，任何计算机程序的错误都被称为“bug”，找出错误则被称为“debug”。

![2.jpg](/assets/img/grace-hopper/2.jpg)

贴有飞蛾的研发记录薄，现藏于华盛顿的美国历史国家博物馆。

<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
让计算机这个笨家伙读懂英文
</strong></p>



如今，计算机看起来智商很高，不过再“聪明”的计算机也只能识别和执行特定的“机器语言”：由二进制代码（1和0）表示的特定的指令集合。

曾几何时，计算机程序都是通过这样的机器语言直接编写出来的。这是一项既费时又费脑的繁琐工作：不同型号的计算机有专门根据其硬件结构而设计的专有机器语言。程序员不仅需要熟记所有这些指令，还需要在编程过程中将计算机每个工作单元的即时状态考虑在内。并且，这些全是由0和1组成的代码直观性极差，非常容易出错。所以，当时编写程序花费的时间往往是实际运行时间的几十甚至几百倍。

面对这些困扰，葛丽丝 · 霍普提出开发高级编程语言的想法，让人们能够以接近英文写作的方式来编写程序。这其中自然而然地产生了一个问题：如何才能让计算机读懂英文？面对这个像天方夜谭一样的难题，霍普提出，能否建立一种机制，能够在程序运行时根据一定的准则自动将这样的自然语言转化成机器能理解的命令？霍普提出的这个概念，正是为今天计算机界所熟知的编译器（Compiler）。

实现这一构想的机会在霍普于1949年加入埃克特-莫奇莱电脑公司（Eckert-Mauchly Computer）时终于来临。在她负责的一台叫做UNIVAC I的计算机上，霍普研发出了第一套编译器系统，将近乎英文的程序转换为计算机能够读懂的机器语言。

![3.jpg](/assets/img/grace-hopper/3.jpg)

霍普在UNIVAC键盘前

编译器概念的出现促使大量新的高级编程语言被开发出来，也带来了新的问题：由于各个公司都在使用自行研发的编译器，不同系统下产生的程序各不相容。为此，霍普研发出一套检测程序，以确认程序是否是由同一套编译器编译出来的。1959年，面对编程语言层出不穷、规则混乱的情况，霍普作为首席技术顾问，与军方和民间的专家共同制定了新的适用于任何计算机的编程语言标准。这一标准直接推动了第一个高级商用计算机程序语言“COBOL”的诞生，因此，葛丽丝 · 霍普也被誉为“COBOL 之母”。

<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
“请求原谅总是比得到许可更容易”
</strong></p>



在被问到编译器是否是她最引以为豪的成就时，霍普说：“相比开发出编译器这件事本身，更重要的是意识到我们需要并且能够让操作电脑变得更为简单。没有这样的信念，编译器及其后续成果都不会出现。” 的确，编译器的存在，于今天的计算机世界中显得再自然不过，在当时却是个革命性的概念。人们期望计算机能够做的，正如计算机这个名字所暗示的，充其量不过是一些数据运算而已。当葛丽丝 · 霍普开始开发编译器时，她没有得到公司高层的许可，当时的人们也无法理解这一想法的意义所在。霍普不得不自行着手研究，还需要四处演讲，寻求经费和支持。因为这一想法太具颠覆性，以至于当她向别人展示已成功运行的编译器时，也没有人愿意相信并尝试。对于这段经历，霍普后来有过一段著名的评论：

“请求原谅总是比得到许可更容易。 （It's always easier to ask forgiveness than it is to get permission.）”

今天，学习计算机并不是一件高不可攀的事情。在美国的大学里，有大量的学生会走进计算机基础课的教室，花上一些时间入门，就能写出一些简单而有趣的小程序。而软件工程师和研发人员们能够从繁杂的机器语言中解放出来，将脑力专心集中于实现他们的核心想法，无疑要感谢霍普当年的坚持。

<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
不可思议的葛丽丝（Amazing Grace）
</strong></p>



1966年，60岁的葛丽丝 · 霍普到达美国军方的服役年龄上限，依法退伍。然而，霍普离开仅仅六个月之后，美国海军部就发现有大量他们无力处理的程序，于是修改了原有规章，紧急召回霍普。1971年，霍普再度退休，1972年又再度被美国军方召回。1983年，葛丽丝 · 霍普被里根总统任命为海军准将，而众议院也特别批准让她延长服役年限，继续参与军方计划。当1986年霍普正式退役时，79岁的她也成为了美国退伍时年纪最长的军人。在她的退伍仪式中，霍普被授予国防部杰出服务勋章，这也是国防部为非战斗人员设立的最高奖项。

![4.jpg](/assets/img/grace-hopper/4.jpg)

霍普被授予海军准将

退伍后的葛丽丝 · 霍普并没有闲下来，她不断被各类计算机相关的活动邀请为演讲嘉宾，向人们普及早期计算机及战时的故事。霍普的演讲妙趣横生，其中最著名的还是“葛丽丝 · 霍普纳秒”的故事：在演讲的过程中，霍普被观众席中的军官们问到为什么卫星通讯的速度会这么慢。情急之下，霍普要来一段一英尺（大约30厘米）的导线，并说明这是在真空状态下，光在一纳秒能走过的距离，而在真正的导线中，信号只会走得更慢。同样是利用这样一根导线，霍普向大众解释了为什么想要提高运行速度，电脑需要被造得很小。这些一英尺的导线后来被霍普风趣地称为她的“纳秒们”。

除了在计算机方面的地位无可替代，葛丽丝 · 霍普还是位出色的导师。大批年轻人在她的培养下成为计算机行业内各个领域的专家，并开始了他们自己的研究项目。当年轻人们询问霍普他们的想法是否可行时，霍普总是鼓励他们去尝试。她不断地激励年轻人把握机会去挑战，因为“停在港口的船很安全，但那不是我们造船的目的（A ship in port is safe, but that is not what ships are built for.）”。

在计算机技术突飞猛进的今天，葛丽丝 · 霍普依旧以她的影响力激励着更多年轻人、尤其是年轻女性加入到计算机领域中来。在美国，葛丽丝 · 霍普计算机科学女性峰会（GHC，Grace Hopper Celebration of Women in Computing）是一年一度的致力于推动女性参与计算性研究的科技论坛，每年都会吸引众多该领域的学生、研究人员及工程师的参与。

霍普曾经在墙上挂了一只逆时针转动的钟，以提醒自己不要因为习惯了现有作法而忘记改变。也正如作家杰 · 埃里奥特（Jay Elliot）所说：身为一名百分之百的美国海军，霍普其实深藏着一颗海盗的心。

- - -

<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
参考文献
</strong></p>



- [https://zh.wikipedia.org/wiki/%E8%91%9B%E9%BA%97%E7%B5%B2%C2%B7%E9%9C%8D%E6%99%AE](https://zh.wikipedia.org/wiki/%E8%91%9B%E9%BA%97%E7%B5%B2%C2%B7%E9%9C%8D%E6%99%AE)
- [https://zh.wikipedia.org/wiki/%E6%9C%BA%E5%99%A8%E8%AF%AD%E8%A8%80](https://zh.wikipedia.org/wiki/%E6%9C%BA%E5%99%A8%E8%AF%AD%E8%A8%80)
- [http://americanhistory.si.edu/collections/search/object/nmah_334663](http://americanhistory.si.edu/collections/search/object/nmah_334663)
- [https://en.wikipedia.org/wiki/Grace_Hopper_Celebration_of_Women_in_Computing](https://en.wikipedia.org/wiki/Grace_Hopper_Celebration_of_Women_in_Computing)
- [https://en.wikipedia.org/wiki/Grace_Hopper](https://en.wikipedia.org/wiki/Grace_Hopper)
- [https://en.wikipedia.org/wiki/Harvard_Mark_I](https://en.wikipedia.org/wiki/Harvard_Mark_I)
- [http://www.360doc.com/content/15/0702/22/11844837_482246171.shtml](http://www.360doc.com/content/15/0702/22/11844837_482246171.shtml)
- Computer Oral History Collection, 1969-1973, 1977 Grace Murray Hopper Interview, January 7, 1969, Archives Center, National Museum of American History
- [http://whatis.techtarget.com/definition/Grace-Hopper-nanosecond](http://whatis.techtarget.com/definition/Grace-Hopper-nanosecond)
- [http://www.amazingwomeninhistory.com/amazing-grace-hopper-computer-programmer/](http://www.amazingwomeninhistory.com/amazing-grace-hopper-computer-programmer/)


- - -
<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
作者简介
</strong></p>



刘文舜，杜克大学（Duke University）计算机系毕业，现湾区终日与bug奋战的软件工程师。

- - -
<p style="line-height: normal; font-size: 16px; font-family: 微软雅黑; color: rgb(0, 187, 170); box-sizing: border-box; padding: 0px; margin: 10px 0px; text-align: left;"><strong>
版权声明
</strong></p>



本文为本站成员原创，版权及其他合法权利均归作者与本站共同所有。任何媒体或网站未经本站授权不得转贴或以其他方式复制发表本文。寻求授权请联系： contact@stemgirlschina.com

本文图片来自于NASA。

