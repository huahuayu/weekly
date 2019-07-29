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

## 2019年第13周
1. [信息安全] 偶然看到一个黑技术的repo https://github.com/tiancode/learn-hacking 我蛮感兴趣的，有空来学习下，从这里衍生看到https://www.hackthissite.org/ 里面有一些黑客挑战题，也算是一个黑客社区，回头来学习下。  
2. [chrome插件] [fireshot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg) chrome插件可以滚动截图。以前我一直用snagit，因为它支持任意窗口的滚动截图，但是最近的snagit版本（mac版）好像滚动截图都不好使了。现在fireshot至少能满足我浏览器内截图需求。  
3. [效率工具] 说到截图，图片上传图床也是头疼的事，[picgo](https://github.com/Molunerfinn/PicGo)是一个支持多个图床的便捷上传图片的软件，强烈推荐!   

## 2019年第14周
1. [mac技巧] mac右键用vscode打开文件夹 https://github.com/Sankra/OpenFolderInVSCode  
2. [小工具] 克隆自己所有的github repo https://www.npmjs.com/package/clone-all-github-repos , 安装的时候会要求输入github用户名和access token, 之后就可以用`cagr`命令克隆自己所有的repos到本地文件夹  
3. [程序员漫画] 偶然看到这个程序员漫画，搞笑，和西乔的神秘的程序员们有的一拼 https://instagram.com/themonkeyuser  
4. [mac查看进程和端口号绑定] 因为mac下的netstat和linux下的netstat有些不一样([究其原因](https://tonydeng.github.io/2016/07/07/use-lsof-to-replace-netstat/))，我一直为此所困，在mac下要用lsof命令替代昨，但是我又记不住这么长的命令，昨天看到一个Stack Overflow回答，彻底解决了我的问题，把lsof命令封装成一个方法，赞 https://stackoverflow.com/a/30029855/6797425   
5. [命令行技巧] 当常用的路径比较深的时候，cd过去比较麻烦，可以在zshrc文件中加入 `alias mydir='cd /a/very/very/very/long/dir'` 以后直接在命令行中敲mydir就可以到dir目录了，非常方便  

## 2019年第19周
1. [休闲] 在线小霸王游戏 https://yikm.net/ 游戏全，体验棒，很怀旧的感觉  
2. [mac软件] annotate这个mac软件好用，制作gif的 https://itunes.apple.com/us/app/annotate-capture-and-share/id918207447?mt=12  
3. [云储存软件] 自从金山快盘退出市场后我就开始使用坚果云，已经使用了多年，产品做得很棒，全平台支持，支持找回历史文件，强力推荐。  

## 2019年第21周
1. [git] [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)这篇文章估计是gitflow相关话题引用最多的一篇文章，值得认真学习https://www.atlassian.com/git/tutorials/comparing-workflows 进一步做了阐述，中文相关的翻译github项目star都达到几千了   
2. [网站跨域] 看这两个网站就够了，第一个讲原理，第二个讲实用：https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS https://enable-cors.org

## 2019年第23周
1. [技术文档] rackspace的技术文档规范，我觉得他们技术文档写的很好，原来是有制定一个技术文档写作规范，我要深度学习一下，这是专业素养的一部分 https://developer.rackspace.com/docs/style-guide/

## 2019年第26周  
1. [效率应用] Microsoft todo有了官方Mac app了，appstore可以下载，喜大普奔。在此之前我用电脑时都是访问web版  
2. [markdown] 写markdown很爽，但是遇到要插入table时如果手敲就有麻烦，要敲很多竖线。为了解决这个常见问题，我想到应该会有相关的alfred插件，一搜，果然是有的。体验还非常不错。https://github.com/crispgm/alfred-markdown-table  
3. [实用工具] 贴代码片段/日志并分享的在线服务 https://pastebin.com/ ，方便在网络上跟人说明问题。类似的服务还有https://pastebin.ubuntu.com/ 
4. [在线简历] 这个简历模板非常简洁漂亮，在线投递简历的时候就可以直接给链接了，还可以下载pdf，很棒 https://crispgm.github.io/resume/resume.html  
5. [在线vscode] 这个项目可以让vscode在线访问，体验非常棒了，可以用来远程面试，哈哈 https://github.com/cdr/code-server

## 2019年28周
1. [效率应用] 通过alfred管理ssh连接，实现和windows下的xshell功能  https://github.com/projectweekend/alfred-iterm-ssh-workflow  
2. [github markdown图标] github项目readme里加上一些图标效果更友好，这里是在线的图标列表 https://www.webfx.com/tools/emoji-cheat-sheet/ 复制图标代号就可以使用了  

## 2019年31周
1. [Mac技巧] Mac下的文件管理器finder搜索栏，我一直觉得不太好用，原因是搜索的时候默认搜索整个Mac（抓狂），最近我才知道可以设置默认搜索当前文件夹，设置方法是Finder->perferences->advance->最下方选择search the current folder  



