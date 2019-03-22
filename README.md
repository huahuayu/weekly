# 世明的每周分享
这里分享我接触到的有用的、有趣的、有启发的东西，致敬[阮一峰的每周分享](http://www.ruanyifeng.com/blog/weekly/)
## 2019年第9周
1. [技术文章] 各个linux发行版的包管理命令详解 from digitalocean，我发现云服务提供商现在都有建立自己的知识库，部分官方贡献，部分是用户贡献内容，质量都比较高，以下就是一篇，系统的总结各种linux发行版的包管理命令  
https://www.digitalocean.com/community/tutorials/package-management-basics-apt-yum-dnf-pkg  
2. [手机应用] Microsoft To-Do  
我没想到微软有这么一款应用，这个todo应用超过我的期待，我已经把它放在我的手机第一屏了，免费软件做出了收费版的体验！ios应用商店有下载，不知道有没有安卓版。
3. [技术漫画] how dns works  
https://howdns.works/ 以漫画的方式讲解dns的工作原理，fun!  
4. [技术漫画] how https works  
https://howhttps.works/ 以漫画的方式讲解https的工作原理，fun！ 
5. [技术文章] why dns is important and how it works  
https://dyn.com/blog/dns-why-its-important-how-it-works/
## 2019年第10周
1. [架构] 10 Common Software Architectural Patterns in a nutshell，10种常见企业软件架构总结
https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013

包含以下架构模型，言简意赅  
```
Layered pattern
Client-server pattern
Master-slave pattern
Pipe-filter pattern
Broker pattern
Peer-to-peer pattern
Event-bus pattern
Model-view-controller pattern
Blackboard pattern
Interpreter pattern
Event-bus pattern
```
2. [github repo] 产品级的注册登录服务by java  
https://github.com/Baeldung/spring-security-registration . 
3. [chrome插件] octotree, 在浏览github项目时该插件会在屏幕左边列出文件树，方便查看和跳转  
https://chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagc?hl=en-US&utm_source=chrome-ntp-launcher  
4. [github repo] go网络编程  
https://github.com/tumregels/Network-Programming-with-Go
5. [方案] 北森招聘系统SaaS，适合不想自己开发招聘系统的公司，花点钱用别人成熟方案挺好的。不要把招聘全部依托于拉勾、boss、猎聘这样的网站，自己有个招聘渠道不好么，至少我觉得逼格高点     
https://www.beisen.com/  
## 2019年第11周
1. [效率工具][draw.io](https://draw.io)是一个在线画流程图的好工具，我用了多年了，类似还有一个叫[lucidchart](https://www.lucidchart.com)的，收费，但感觉没有draw.io好。draw.io完全可以替代windows下的visio，配合google drive来用更棒。同时它还提供mac桌面软件，可以离线使用。  
2. [开发工具][yeoman](https://yeoman.io)是一个代码生成工具，可以按最佳实践生成项目骨架。有很多开发者贡献了不少生成器，可以直接使用，[点此查看](https://yeoman.io/generators/)，你也可以制作自己的代码生成方案并共享  
3. [小技巧][.dotfile](https://github.com/huahuayu/.dotfile)是我从朋友那边借鉴的，这是放在home目录下的隐藏文件夹，里面集中了一些我自己的常用软件配置，包括zsh,vim,git和其他个性化的脚本等。用软连接的方式链接到配置文件的路径，用github做版本管理。使用之后我感觉很爽，配置都集中了，有延续性，独一无二的一份配置永远跟着我，即便换一台新电脑(mac/linux)，只要git拉取一下，很快就可以用的顺手。其实现在这是很普遍的做法了，github上N多dotfile的库，有些大神的dotfile有几万个star，[点此了解](https://github.com/search?q=dotfile)。这些高star的dotfile可以借鉴，但是配置这东西就是要个性化的，适合自己的就是好的。  
4. [在线培训] [实验楼](https://www.shiyanlou.com/)是一个在线提供上机环境(vm)的IT培训网站，他们的口号是"动手做实验，轻松学IT"，mooc现在有很多家，像实验楼这种的我只看到这一家，我觉得非常用心，也非常良心，很多免费课程，实操为主。get your hands dirty对IT人来说非常重要，直接上手练几次就会了。
5. [golang weekly] go开发者最好邮件订阅一下[golang weekly](https://golangweekly.com/)，里面的文章质量都很高，能接触到社区的最新动态。  
6. [效率工具] [Swaggo](https://github.com/swaggo) 是一个效率工具，在写golang程序的时候只要按规则写好注释，swaggo能帮你自动生成在线api文档。 
## 2019年第12周
1. [电脑加速] mac上有一个应用叫dashboard，聚合计算器、天气之类的一个挂件应用，99.9%的人一般都不会去用的（计算器和天气之类的都有独立的app，谁会去用挂件呢，而且现在也没有开发者开发更多的挂件），但它一直在后台运行，运行`defaults write com.apple.dashboard mcx-disabled -boolean YES && killall Dock`可以将dashboard关闭掉，能节省1%是1%。 
2. [效率工具] mac下的wps2019真的好用，现在可以画流程图和mindmap了，而且整合成一个应用 wps2019，新建文件的时候再选word,excel,ppt,flowchat,mindmap。就mac下的体验来说完胜Microsoft office。以后画流程图我可能就用wps了（替换原来的[draw.io](https://draw.io)）。  
3. [效率工具] Alfred是一个可以替代mac自带的spotlight软件，是mac效率神器，据Alfred自带的统计，平均每天我要使用14次，一年使用5000多次。[关于它的用法可以写本书](http://louiszhai.github.io/2018/05/31/alfred/)，我还只用到部分功能：本地文件/应用搜索、在线搜索引擎一键搜索、自定义的workflows功能。alfred可以免费使用，但是workflows功能是收费版才有的，也不贵，折合人民币两百多块，而且很良心：一次购买，永久升级。强烈推荐使用收费版，因为workflows是它的精华。我在github上有分享一个我定制的workflows插件，叫[all in one search](https://github.com/huahuayu/all-in-one-search-workflows)  
4. [效率工具] iterm2是mac下一个terminal软件，比自带的terminal软件好用很多，建议开启每日tips，不要disable掉它，每天使用的时候学习一个小技巧，会越来越得心应手  
5. [效率工具] [tmux](https://hackernoon.com/a-gentle-introduction-to-tmux-8d784c404340)是一个命令行软件，可以在一个ssh连接的基础上开多个工作窗口，执行不同的任务。即便因为网络原因ssh断开连接，当再次连上ssh时，tmux里面的任务不会受影响。  


