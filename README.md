# <p align="center">OpenClash-Rule</p>
&emsp;&emsp;在科学上网的使用中，固然可以在一些GitHub上的一些自动抓取节点的项目上白嫖一些不稳点的节点使用，但是目前的机场的价格战，让人很难不心动，但对于一些机场主提供的订阅节点链接，有的里面只是添加了一点最基础的规则，让你不至于无法成功“出国”。<br>
&emsp;&emsp;对于这样的状况最简单的是找到一个订阅转换网站，在里面选择你对应的客户端，然后添加你认为合适的开源项目维护的访问命中规则，这样你的机场链接订阅后的效果就变得好用，且高效。
## [ACL4SSR](https://acl4ssr-sub.github.io/)
&emsp;&emsp;这就是这样一个很直观的订阅转换网站，按我上面的描述，很快你就可以得到一个用的舒服，但又可能没有那么舒服的使用效果。
## [ACL4SSR_Online.ini](https://github.com/ACL4SSR/ACL4SSR/blob/master/Clash/config/ACL4SSR_Online.ini)
&emsp;&emsp;我喜欢用Clash，于是基于这一通用规则，添加了一些在学习如何编辑规则中，觉得有用的规则和策略组，并在其中加了一些嵌套，实现更方便的管理。<br>
&emsp;&emsp;上传为了对应上面网站的`MowYw.ini`的远程配置端口，将其挂载在GitHub上，以后客户端更新订阅时，可以访问其中引用的内容。<br>
&emsp;&emsp;打开源码模式，你将会看到相较于原版的修改，并添加了相应的注释来辅助理解。于是你可以来编写更适合自己的规则文件。<br>
&emsp;&emsp;为什么要这样做，因为当你添加某一规则或是覆写了配置后，如果你的订阅删除，或是软路由重置后，一切都将丢失，一两条规则还好，多了的话，真叫人抓马。
### 如何使用
1、进入`ACL4SSR`网站后，粘贴你购买到的机场订阅地址，这里仅仅添加一个订阅的话，还不能让你完全体验到自己修改规则的好处，当你拥有高速但贵、慢却便宜的多个机场组合式，你就可以利用规则来使用一些下载、观影走廉价机场，甚至是`低倍率节点`，游戏等低延迟的项目走高速但高倍率的节点等。<br>
&emsp;&emsp;这里推荐一个目前的廉价机场：[游隼云](https://falcocloud.730894.xyz/#/register?code=TO6hDfIA)，这价格买不了吃亏买不了上当，自用感觉还好，如果跑路的话，手动狗头。<br>
2、选择你对应得客户端。经过实验发现该网站无法对仅支持Clash Verge的机场来实现转换，比如上面的廉价机场，`咬牙切齿`<br>
3、在远程配置中，你需要注意这里粘贴的地址不是`MowYw.ini`的地址，而是点击文件进去后，再点击右上`Raw`的网址<br>
4、在后端地址中，一般不用改动，如果转换后的订阅网址，在你未科学的安卓手机中存在无法下载订阅的情况，逐个更换后端地址再来尝试。<br>
&emsp;&emsp;`PS`但往往这里就是你的订阅泄露的可能存在，但是使用`本地版后端`的话，又需要保证在你的订阅定时更新时，这个本地端是开的，于是这里也就是建议软路由、且安装有Docker的用户可以本地部署一个本地端。看后续再来添加这一部分。<br>
5、至此你就可以愉快的生成独属于你的规则订阅啦！
  <br><br><br><br>




## 碎碎念
&emsp;&emsp;初中时在IPAD上玩到的狂野飙车8，很好玩，世界赛把把第一，小小的骄傲下。高中没时间，也不让放开了玩了，中间于是就中断了。<br>
&emsp;&emsp;上了大学，有了自己的手机后，某一天又突然想到了这款游戏，就开始搜索这个游戏在安卓上有没有，发现原来没有登录中国。<br>
&emsp;&emsp;于是在一通钻研下，科学，谷歌都搞上，终于是又玩到了这个游戏，发现自己依旧是爱得深沉，但是后来用点击器，加上特殊关卡的刷金币，终走上了毁掉对一个游戏的热爱就是开挂的末路，不过后来游戏也越改越陌生了。不过即是现在换了苹果手机，依旧在存储中给他留了位置，即使很久没有再打开这个游戏。<br>
&emsp;&emsp;`PS`没想到续作狂野飙车9是如此得让我看不上！苹果和安卓怎么不能互通数据！我的老存档！以前也用的不是自己的AppleID！！！<br><br>
&emsp;&emsp;一开始上道是老王这个免费VPN，后来发现了SSR这个红飞机软件，但都是可用的状态，后来发现了Clash，原来还有这样好用的软件！遗憾的是，即使依旧能用，众所周知，停止维护在了那年的年末，不过好在后继有人，Clash Mate等变体软件还在继续维护。<br>
&emsp;&emsp;现在捡了个J1900的工控机来做软路由OpenWrt跑OpenClash，也安装了docker,在里面跑Ubuntu，或是Home Assistant等等，很多的玩法，新奇了一两周，就还是归于稳定，真的没有那么多需求，对于一个在外打工的人来说。以前也是体验过12元硬路由刷机的人，软路由是真的从容！<br>
&emsp;&emsp;也在陆续捡ARM开发板的漏，忍不住剁手啊！怎么说呢，体验上是比不过X86的，不过功耗是真的低，不过现在也不高，软路由加硬路由的纯AP，也才8W。
