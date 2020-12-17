### 本repo存在的意义完全在于[privacy-protection-tools/anti-AD](https://github.com/privacy-protection-tools/anti-AD "privacy-protection-tools/anti-AD")及其目前的维护者[gentlyxu](https://github.com/gentlyxu "gentlyxu")
###### 创建这个repo的目的是为了提醒打算或正在使用此列表的用户了解一下维护者的所作所为再做决定是否要承担风险继续使用。
<br/>

<p align="center">
可能我这辈子都<strong>根本不会去访问</strong>这些藏在列表深处的“加料”网站， 
</p>
<p align="center">
但是我依然持与对待GFW相同的观点：<strong>我可以不去看，但我去看的权利不能被轻易剥夺。</strong>  
</p>



Update：
-- 
[![Anti anti-AD](https://img.shields.io/badge/Anti-anti--AD-da282a?style=flat-square)](https://github.com/Mosney/anti-anti-AD)
[![GitHub issues](https://img.shields.io/github/issues/Mosney/anti-anti-AD?style=flat-square)](https://github.com/Mosney/anti-anti-AD/issues)
[![Fork on GitHub](https://img.shields.io/github/forks/Mosney/anti-anti-AD.svg?style=flat-square)](https://github.com/Mosney/anti-anti-AD/fork)
[![GitHub license](https://img.shields.io/github/license/Mosney/anti-anti-AD?style=flat-square)](https://github.com/Mosney/anti-anti-AD/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FMosney%2Fanti-anti-AD)](https://twitter.com/intent/tweet?text=%E6%88%91%E5%9C%A8GitHub%E4%B8%8A%E5%8F%91%E7%8E%B0%E4%BA%86anti-anti-AD:&url=https%3A%2F%2Fgithub.com%2FMosney%2Fanti-anti-AD)
[![Star on GitHub](https://img.shields.io/github/stars/Mosney/anti-anti-AD.svg?style=social)](https://github.com/Mosney/anti-anti-AD/)

- 反复横跳的[gentlyxu语录总结](/Quotations.md)
- [其它质疑的声音](/OthersVoices.md) (仅限在404之前被记录下的)  
- [神奇的屏蔽条目](/AmazingEntries.md) (目前来源仅限issue区反馈出的，实际列表中还有多少这样的条目不得而知)
- 相关讨论：
  - https://github.com/AdguardTeam/AdGuardHome/issues/1988
  - https://github.com/collinbarrett/FilterLists/issues/1674
  - https://github.com/badmojr/1Hosts/issues/22

TLDR（太长不看版）：
--
**鉴于原repo所有者喜欢删帖，此处给出以下图片[出处](https://github.com/privacy-protection-tools/anti-AD/issues/10 "出处")和[Archive存档](https://archive.md/W1ttN)**  
###### (由于当时没有想到讨论会以404的方式终结，故第二张图对应的[issue](https://github.com/privacy-protection-tools/anti-AD/issues/140)没有存档，只有GitHub的回复邮件提醒可供一窥)  

![image](https://user-images.githubusercontent.com/22477230/84666132-48fe6780-af53-11ea-96cc-fe8104b766e6.png)
![image](https://user-images.githubusercontent.com/22477230/84666526-c4601900-af53-11ea-95c7-13495837d670.png)

此处引用[neoHost](https://github.com/neoFelhz/neohosts "neoHost")README：
> <img src="https://i.loli.net/2017/10/26/59f16e54c30af.png" alt="logo" width="100" height="100" align="right" />
>
># neoHosts
>
>> **自由、负责、克制** 的去广告 Hosts
>
>## Introduction 介绍
>
>- 自由：我们使用 `MIT & SATA` **自由协议**而不是 `CC BY-NC-ND` 这样的非自由协议，希望能够促进和帮助更多项目
>- 克制：我们保证**不因个人喜好屏蔽非广告有关网站**；我们会仔细研究和分析，**我们不会随意屏蔽任何一个域名**
>- 负责：我们不搞“捐赠才能反馈”、不搞 VIP 特权。**所有用户都应该能免费、完整地使用本项目、自由地反馈问题**


完整故事线：
--
在五月的某一天，偶然发现正在使用的过滤器列表[anti-AD](https://github.com/privacy-protection-tools/anti-AD "anti-AD")夹杂了不属于广告、追踪以及隐私风险的域名，遂到此列表repo下开启了一个[issue #140](https://github.com/privacy-protection-tools/anti-AD/issues/140)询问：
> ## 请问针对法轮功等域名的黑名单是从上游引入的吗？ (#140)    
>   
> 看到几个法轮功域名被过滤，请问是从上游某个列表引入的吗？
> 这些条目不符合[README](https://github.com/privacy-protection-tools/anti-AD/blob/master/README.md)中所述的用途，建议移除条目或添加说明。
> 此处引用[neoHost](https://github.com/neoFelhz/neohosts "neoHost")的做法，即创建多个版本的列表并在README中明确标识：
> > ### [Full Hosts](https://cdn.jsdelivr.net/gh/neoFelhz/neohosts@gh-pages/full/hosts)
>> 
>> 包含全部数据，仅推荐强迫症使用。相比 Basic Hosts，Full Hosts 额外屏蔽了以下内容：
>> 
>> - JS Miner 挖矿
>> - 百度全家桶的全天候定位记录
>> - 各类统计服务（仅屏蔽 JS、不屏蔽控制台）
>> - 常见下载劫持
>> - 360 和百度的部分软件下载
>> - CNNIC 根证书劫持
>> - 法轮功、ISIS、银河联邦等可能令人反感的激进宗教内容网站
>> 
>> - [AdGuardHome 兼容版](https://cdn.jsdelivr.net/gh/neoFelhz/neohosts@gh-pages/full/hosts.txt)
>

令人瞠目的是，就在几个月前曾经信誓旦旦的表示坚决摒弃夹带私货的行为（见上图），现如今居然会用`“是的。并且不会被加白。本人亦极其厌恶SB轮子”`这样简单粗暴的话语作为对自己加料行为的回应。尽管如此，这个[issue #140](https://github.com/privacy-protection-tools/anti-AD/issues/140)还是吸引了其它人前来表达自己的看法，由于最终此issue被[gentlyxu](https://github.com/gentlyxu "gentlyxu")删除，只能通过邮件提醒一窥当时的comment：
![image](https://user-images.githubusercontent.com/22477230/83049623-0cd79580-a07e-11ea-94e6-40914c17ca69.png)

最开始觉得这个列表虽然名字和介绍都颇为妄诞，但是整体上质量不错，可以拿来一用，特别是维护者处理反馈和更新列表都很勤快，让人颇有信心。也正是如此我也从其它没有包含的列表当中搜集没有覆盖到的域名[提交上去](https://github.com/privacy-protection-tools/anti-AD/issues?q=is:issue+author:Mosney)（[Archive存档](https://archive.md/GaD1Y)），也有在积极的反馈误伤。但是等我看到邮件点击进issue的时候，只剩下了GitHub的404页，现在再回头看维护者[gentlyxu](https://github.com/gentlyxu "gentlyxu")几个月前信誓旦旦踌躇满志的话只能用可笑来形容。
>我特别希望大家各抒己见。anti-AD是综合著名过滤列表的广告屏蔽、隐私保护工具，所有上游源列表都同等的并且持续的处于考察状态，发现夹带私货并且anti-AD无法修正的情况时，将会剔除此上游列表，不管它有多么著名，多么权威。我始终相信总有一群人，愿意靠自己的力量，创造属于心中理想的完美乌托邦。而开源让这一切成为了可能！

于是就又开了个[issue #145](https://github.com/privacy-protection-tools/anti-AD/issues/145)（[Archive存档](https://archive.vn/J4TKt) ） ，当然这个issue也自然是难逃被直接删除的命运。

不知是1k+的star让[gentlyxu](https://github.com/gentlyxu "gentlyxu")有点膨胀还是有“刺头”敢于挑战他的权威抑或是其它原因，issue区就立了个新规矩：[https://github.com/privacy-protection-tools/anti-AD/issues/146](https://github.com/privacy-protection-tools/anti-AD/issues/146)。本着能少一事不如多一事的原则，跟过去呛了一嗓子：
> 看了一下我前两个被你删的issue上面6条大概也就第5条强行解释能套上，然而实际上你私自往列表里面加料的行为就是利用技术替别人做选择，大概可以称为技术不端，还是技术相关  
> 为了给你以前及以后的行为提供正义基础，建议在“以下几类issue会被删除”里加一条：  
> **7. @gentlyxu 不喜欢的内容**  
> 或者  
> **8.本规定一切解释权归 @gentlyxu 所有**  

当然，必不可少的事后吃瓜链接还是要有：[https://archive.md/0cD6C](https://archive.md/0cD6C)（不知道大家看我提的建议吼不吼哇？）

结尾
--
[neoHost](https://github.com/neoFelhz/neohosts "neoHost")自由、克制、负责的理念，私甚以为然。不知各位看官看到这里是否依然选择继续使用这个夹杂着维护者个人喜好的“去广告列表”呢？这种行为跟**[yhost](https://github.com/vokins/yhosts)曾经**因个人喜恶屏蔽一号店、海信、魅族、Flyme、探探、淘宝、京东联盟等网站的[行为](https://github.com/vokins/yhosts/wiki/%E9%83%A8%E5%88%86%E9%97%AE%E9%A2%98%E8%AF%B4%E6%98%8E)别无二致。[gentlyxu](https://github.com/gentlyxu "gentlyxu")作为一个主打广告屏蔽和隐私保护列表的唯一维护者，在列表中暗自加料做替别人选择这种份外的事情居然还沾沾自喜，拿着大部分都是来源于其它既有列表的数据厚颜自我加冕，号称是“目前中文区命中率最高的广告过滤列表”，既无德也不知耻。你可能同我一样，正常情况下根本就不会去访问被[gentlyxu](https://github.com/gentlyxu "gentlyxu")“加料”的“轮媒”及其相关的网站，但是我依然持与对待GFW相同的观点：**我可以不去看，但我去看的权利不能被轻易剥夺。**

**最后推荐一些其它优秀且同样具有屏蔽广告、防止追踪等功能的列表：**
- [乘风广告过滤规则](https://gitee.com/xinggsf/Adblock-Rule/raw/master/rule.txt)
- [乘风视频广告过滤](https://gitee.com/xinggsf/Adblock-Rule/raw/master/mv.txt)
- [大圣净化](https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts)
- [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)  SSR去广告规则/GFWList规则/Clash规则碎片
- [AdGuard Simplified Domain names filter](https://github.com/AdguardTeam/AdGuardSDNSFilter/raw/gh-pages/Filters/rules.txt)  AdGuardHome 使用的默认列表
- [AdAway](https://github.com/AdAway/adaway.github.io/raw/master/hosts.txt)  AdAway是使用hosts文件的Android开源广告拦截器
- [malwaredomainlist](https://www.malwaredomainlist.com/hostslist/hosts.txt) malwaredomainlist恶意软件域列表是一个非商业社区项目
- [由 NextDNS 收集的各种用途的列表](https://github.com/nextdns/metadata/tree/master/privacy/blocklists)  也可在[NextDNS控制台](https://my.nextdns.io/xxxxxx/privacy)中查看
- ~~[neoFelhz/neohosts](https://github.com/neoFelhz/neohosts)  自由·负责·克制 去广告 Hosts 项目~~ `缺乏维护`
- ~~[vokins/yhosts](https://github.com/vokins/yhosts)  已由[VeleSila/yhosts](https://github.com/VeleSila/yhosts)接手~~ `同样包含主观条目`


***若GitHub访问受限可使用具有中国大陆地区网络的[jsDelivr](http://www.jsdelivr.com/)加速列表源***  
*使用方法：https://cdn.jsdelivr.net/gh/用户名/仓库名@分支/文件路径*

**不在墙内的用户更推荐直接使用[NextDNS](https://nextdns.io/)，更加方便快捷，进可按需定制，退可一键傻瓜化，其中也包含了众多不同用途的屏蔽列表可供按需求自由选择，当然也可以单独拿出来在其它地方使用。**  
> https://github.com/nextdns/metadata/tree/master/privacy/blocklists
> ![image](https://user-images.githubusercontent.com/22477230/84682770-b8cb1d00-af68-11ea-8baa-6a24d84f02d6.png)

下面直接给出AdGuardHome的配置文件filter部分，包含大量列表来源，适合懒人直接复制粘贴，请根据需要做出取舍。实际上一两个综合性的规则列表就已足够覆盖大部分情况，在过滤列表上完全没有必要贪多,使用过多列表反而更容易碰上误伤且不好排查具体来自哪个来源。

```
filters:
- enabled: false
  url: https://raw.githubusercontent.com/neoFelhz/neohosts/gh-pages/basic/hosts.txt
  name: neohosts
  id: 1596593476
- enabled: false
  url: https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts.txt
  name: yhost
  id: 1596593477
- enabled: true
  url: https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts
  name: 大圣净化
  id: 1596593478
- enabled: true
  url: https://gitee.com/xinggsf/Adblock-Rule/raw/master/rule.txt
  name: 乘风广告过滤规则
  id: 1596593479
- enabled: true
  url: https://gitee.com/xinggsf/Adblock-Rule/raw/master/mv.txt
  name: 乘风视频广告过滤
  id: 1596593480
- enabled: true
  url: https://gitee.com/cjx82630/cjxlist/raw/master/cjx-annoyance.txt
  name: CJX’s Annoyance List
  id: 1596593481
- enabled: true
  url: https://easylist.to/easylist/easylist.txt
  name: easylist
  id: 1596595437
- enabled: true
  url: https://easylist-downloads.adblockplus.org/easylistchina.txt
  name: easylistchina
  id: 1596595441
- enabled: true
  url: https://easylist.to/easylist/easyprivacy.txt
  name: easyprivacy
  id: 1596595438
- enabled: true
  url: https://easylist.to/easylist/fanboy-annoyance.txt
  name: fanboy-annoyance
  id: 1596595439
- enabled: true
  url: https://raw.githubusercontent.com/banbendalao/ADgk/master/ADgk.txt
  name: ADgk
  id: 1596595440
- enabled: true
  url: https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
  name: Adblock Warning Removal List
  id: 1596595442
- enabled: true
  url: https://www.i-dont-care-about-cookies.eu/abp/
  name: I don't care about cookies
  id: 1596595443
- enabled: true
  url: https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt
  name: AdAway default blocklist
  id: 1596596474
- enabled: true
  url: https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt
  name: AdGuard DNS filter
  id: 1596596475
- enabled: true
  url: https://someonewhocares.org/hosts/zero/hosts
  name: Dan Pollock's List
  id: 1596596476
- enabled: true
  url: https://raw.githubusercontent.com/durablenapkin/scamblocklist/master/adguard.txt
  name: Scam Blocklist by DurableNapkin
  id: 1596596477
- enabled: true
  url: https://raw.githubusercontent.com/DandelionSprout/adfilt/master/GameConsoleAdblockList.txt
  name: Game Console Adblock List
  id: 1596596478
- enabled: true
  url: https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV-AGH.txt
  name: Perflyst and Dandelion Sprout's Smart-TV Blocklist
  id: 1596596479
- enabled: true
  url: https://pgl.yoyo.org/adservers/serverlist.php?hostformat=adblockplus&showintro=1&mimetype=plaintext
  name: Peter Lowe's List
  id: 1596596480
- enabled: true
  url: https://www.malwaredomainlist.com/hostslist/hosts.txt
  name: MalwareDomainList.com Hosts List
  id: 1596596481
- enabled: true
  url: https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/nocoin.txt
  name: NoCoin Filter List
  id: 1596596482
- enabled: true
  url: https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt
  name: Spam404
  id: 1596596483
- enabled: true
  url: https://raw.githubusercontent.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites/master/hacked-domains.list
  name: The Big List of Hacked Malware Web Sites
  id: 1596596484
whitelist_filters:
- enabled: true
  url: https://raw.githubusercontent.com/Mosney/AGHfilter/master/whitelist.txt
  name: whitelist
  id: 1596596485
```
