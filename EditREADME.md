# Github Actions Rss (garss, 嘎RSS! 已收集{{rss_num}}个RSS源, 生成时间: {{ga_rss_datetime}})

信息茧房是指人们关注的信息领域会习惯性地被自己的兴趣所引导，从而将自己的生活桎梏于像蚕茧一般的“茧房”中的现象。

## 《嘎!RSS》🐣为打破信息茧房而生

![](./_media/ga-rss.png)

这个名为**嘎!RSS**的项目会利用免费的Github Actions服务, 提供一个内容全面的信息流, 让现代人的知识体系更广泛, 减弱信息茧房对现代人的影响, 让**非茧房信息流**造福人类~
[《嘎!RSS》永久开源页面: https://github.com/zhaoolee/garss](https://github.com/zhaoolee/garss)


## 主要功能
1. 收集RSS, 打造无广告内容优质的 **头版头条** 超赞新闻页
2. 利用Github Actions, 搜集全部RSS的头版头条新闻标题和超链接, 并自动更新到首页,当天最新发布的文章会出现🌈 标志

邮件内容区开始>
<h2>新蒸熟{{new_num}}个小蛋糕🍰(文章) 生产时间 {{ga_rss_datetime}} 保质期24小时</h2>

{{news}}

<邮件内容区结束

## 已收集RSS列表

| 编号 | 名称 | 描述 | RSS  |  最新内容 |
| :-: | --- | --- | --- |  --- |
| <h2 id="政治新闻">政治新闻</h2> |  | |  | |
| PS001 | 人民日报 |  暂无 | {{latest_content}}  | [订阅地址](https://feedx.net/rss/jingjiribao.xml) |
| PS001 | 端传媒 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/theinitium_rss) |
| PS001 | 经济学人 |  暂无 | {{latest_content}}  |  [订阅地址](https://github.com/yiranzhimo/Rss-Translation/blob/main/rss/Economist.xml) |
| PS001 | 中国话题 |  暂无 | {{latest_content}}  |  [订阅地址](https://china.buzzing.cc/feed.xml) |
| PS001 | 财新网 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/caixin/latest) |
| PS001 | 华尔街日报 |  暂无 | {{latest_content}}  |  [订阅地址](https://github.com/yiranzhimo/Rss-Translation/blob/main/rss/The%20Wall%20Street%20Journal.xml) |
| <h2 id="经济新闻">经济新闻</h2> |  | |  | |
| ES001 | 晚点 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/latepost) |
| ES001 | Bloomberg |  暂无 | {{latest_content}}  |  [订阅地址](https://bloombergnew.buzzing.cc/feed.xml) |
| ES001 | 第一财经 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/yicai/latest) |
| ES001 | 汇率 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/boc/whpj) |
| ES001 | 律动 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/theblockbeats) |
| ES001 | Investing |  暂无 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/investing.xml) |
| <h2 id="其他新闻">其他新闻</h2> |  | |  | |
| OM001 | 睡前消息 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/shuiqianxiaoxi) |
| OM001 | Aeon |  暂无 | {{latest_content}}  |  [订阅地址](https://aeon.co/feed.rss) |
| OM001 | Big Think |  暂无 | {{latest_content}}  |  [订阅地址](https://bigthink.com/feed/all) |
| OM001 | Collider |  暂无 | {{latest_content}}  |  [订阅地址](https://www.collider.space/rss) |
| OM001 | 歪脑 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.wainao.me/rss.xml) |
| OM001 | NOEMA |  暂无 | {{latest_content}}  |  [订阅地址](https://www.noemamag.com/feed/) |
| <h2 id="论坛">论坛</h2> |  | |  | |
| FM001 | Hacker News 热门|  暂无 | {{latest_content}}  |  [订阅地址](https://hn.buzzing.cc/feed.xml) |
| FM001 | V2EX |  暂无 | {{latest_content}}  |  [订阅地址](https://www.v2ex.com/index.xml) |
| FM001 | Reddit 热门 |  暂无 | {{latest_content}}  |  [订阅地址](https://reddit.buzzing.cc/feed.xml) |
| FM001 | 一亩三分地 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/1point3acres/thread/new) |
| FM001 | LessWrong |  暂无 | {{latest_content}}  |  [订阅地址](https://www.lesswrong.com/feed.xml) |
| FM001 | 十年之约博客 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/foreverblog/feeds) |
| FM001 | Xlog |  暂无 | {{latest_content}}  |  [订阅地址](https://xlog.app/feed/latest) |
| FM001 | Bear Blog |  暂无 | {{latest_content}}  |  [订阅地址](https://bearblog.buzzing.cc/feed.xml) |
| FM001 | 积薪 |  暂无 | {{latest_content}}  |  [订阅地址](https://firewood.news/rss.xml) |
| FM001 | 知乎热榜 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/zhihu/hotlist) |
| FM001 | Dochub |  暂无 | {{latest_content}}  |  [订阅地址](https://www.dochub.wiki/feed/) |
| <h2 id="周报">周报</h2> |  | |  | |
| NL001|Daily Productivity Sharing |  暂无 | {{latest_content}}  |  [订阅地址](https://letters.acacess.com/rss/) |
| NL001| Interconnected |  暂无 | {{latest_content}}  |  [订阅地址](https://interconnected.blog/rss/) |
| NL001| 事不过三 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/zhubai/via) |
| NL001| 光明王 |  暂无 | {{latest_content}}  |  [订阅地址](https://lordoflight.substack.com/feed) |
| NL001 | 湾区日报 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/wanqu/news) |
| NL001 | Hello Github |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/hellogithub/volume) |
| NL001 | 假设检验 |  暂无 | {{latest_content}}  |  [订阅地址](https://jiashejianyan.com/rss/) |
| NL001 | 棱镜通讯 |  暂无 | {{latest_content}}  |  [订阅地址](https://wangyurui.com/feed.xml) |
| NL001 | 维舟 |  暂无 | {{latest_content}}  |  [订阅地址](https://weizhou.substack.com/feed) |
| NL001 | AwesomeVisa Exodus |  暂无 | {{latest_content}}  |  [订阅地址](https://exodus.awesomevisa.com/rss/) |
| NL001 | 老胡的周刊 |  暂无 | {{latest_content}}  |  [订阅地址](https://weekly.howie6879.com/rss/rss.xml) |
| NL001 | 龙爪槐守望者 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.ftium4.com/rss.xml) |
| NL001 | 54321-Weekly |  暂无 | {{latest_content}}  |  [订阅地址](https://github.com/versun/54321-Weekly/releases.atom)|
| NL001 | 1Link.Fun 科技周刊 |  暂无 | {{latest_content}}  |  [订阅地址](https://1link.fun/blog/index.xml)|
| NL001 | Dishing The Data |  暂无 | {{latest_content}}  |  [订阅地址](https://dishingthedata.substack.com/feed)|
| NL001 | 没有离开地球的原因 |  暂无 | {{latest_content}}  |  [订阅地址](https://redend110.substack.com/feed)|
| NL001 | Unsupervised Learning |  暂无 | {{latest_content}}  |  [订阅地址](https://redend110.substack.com/feed)|
| NL001 | 工劳小报 |  暂无 | {{latest_content}}  |  [订阅地址](https://fed.laborinfocn3.com/rss/)|
| NL001 | 富于理性 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/zhubai/havefun)|
| <h2 id="博客">博客</h2> |  | |  | |
| BS001 | 雪球专刊 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/xueqiu/column/3746414875)|
| BS001 | 少数派 |  暂无 | {{latest_content}}  |  [订阅地址](https://sspai.com/feed) |
| BS001 | UNTAG |  暂无 | {{latest_content}}  |  [订阅地址](https://rss.utgd.net/feed) |
| BS001 | 有知有行 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/youzhiyouxing/materials) |
| BS001 | 东西智库 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.dx2025.com/feed) |
| BS001 | TO-D 观察室 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/tod_magazine) |
| BS001 | 老胡周刊资源分享频道 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel//howie_weekly) |
| BS001 | Money Orders |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/Harry_public) |
| BS001 | Financial News And Report |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/financialnews666) |
| BS001 | 你不知道的内幕消息 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/inside1024) |
| BS001 | Newlearnerの自留地 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/NewlearnerChannel) |
| BS001 | 扫地僧笔记 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/lover_links) |
| BS001 |Know Thyself |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/master_thyself) |
| BS001 | 小声读书 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/weekly_books) |
| SS001 | 冰器库 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/ifanbing) |
| BS001 | 随机漫谈 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/what_to_read_today) |
| BS001 | chatGPT中文社区 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/LptTech) |
| BS001 | ALL About RSS |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/aboutrss) |
| BS001 | 数学及其应用 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/mathematics_and_its_applications) |
| BS001 | Yu's life |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/pseudoyulife) |
| BS001 | 书伴 |  暂无 | {{latest_content}}  |  [订阅地址](https://feeds.feedburner.com/bookfere) |
| BS001 | PC精选 |  暂无 | {{latest_content}}  |  [订阅地址](https://project-gutenberg.github.io/Pincong/post/index.xml) |
| BS001 | 见字如面 |  暂无 | {{latest_content}}  |  [订阅地址](https://hiwannz.com/feed) |
| BS001 | 一方天地 |  暂无 | {{latest_content}}  |  [订阅地址](https://emmmme.com/feed.xml) |
| BS001 | 卢昌海的博客 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.changhai.org/feed.xml) |
| BS001 | MaxOS |  暂无 | {{latest_content}}  |  [订阅地址](https://maxoxo.me/rss/) |
| BS001 | 谢益辉 |  暂无 | {{latest_content}}  |  [订阅地址](https://yihui.org/index.xml) |
| BS001 | 王登科 |  暂无 | {{latest_content}}  |  [订阅地址](https://greatdk.com/feed) |
| BS001 | 扯氮集 |  暂无 | {{latest_content}}  |  [订阅地址](http://weiwuhui.com/feed) |
| BS001 | 数字游民部落 |  暂无 | {{latest_content}}  |  [订阅地址](https://jarodise.com/rss.xml) |
| BS001 | 林海草原 |  暂无 | {{latest_content}}  |  [订阅地址](https://lhcy.org/feed) |
| BS001 | 王五四文集 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/blogs/wang54/2023) |
| BS001 | Owen|  暂无 | {{latest_content}}  |  [订阅地址](https://www.owenyoung.com/atom.xml) |
| BS001 | Pseudoyu|  暂无 | {{latest_content}}  |  [订阅地址](https://www.pseudoyu.com/zh/index.xml) |
| BS001 |炜晨|  暂无 | {{latest_content}}  |  [订阅地址](https://weichen.blog/cn/blog/index.xml) |
| BS001 | chinese future|  暂无 | {{latest_content}}  |  [订阅地址](https://www.chinese-future.org/home?format=rss) |
| BS001 | 员外|  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/luxiangdong/archive) |
| BS001 | 虹线|  暂无 | {{latest_content}}  |  [订阅地址](https://1q43.blog/feed) |
| BS001 | neverland |  暂无 | {{latest_content}}  |  [订阅地址](https://type.cyhsu.xyz/feed.xml) |
| BS001 | 夜法之书 |  暂无 | {{latest_content}}  |  [订阅地址](https://blog.17lai.site/atom.xml) |
| BS001 | 拾月书签 |  暂无 | {{latest_content}}  |  [订阅地址](https://pocket.skyue.com/feed/atom?) |
| BS001 | 拾月博客 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.skyue.com/feed/)|
| <h2 id="播客">播客</h2> |  | |  | |
| PD001 | 知行小酒馆 |  暂无 | {{latest_content}}  |  [订阅地址](https://feed.xyzfm.space/j8yp8gxkmgqr) |
| PD001 |一席 |  暂无 | {{latest_content}}  |  [订阅地址](https://feed.xyzfm.space/jq7xytwpykrg) |
| PD001 |声东击西 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.etw.fm/rss) |
| PD001 | 乱翻书 |  暂无 | {{latest_content}}  |  [订阅地址](https://feed.xyzfm.space/yxuruh3f9mc4) |
| PD001 | 疯投圈 |  暂无 | {{latest_content}}  |  [订阅地址](https://crazy.capital/feed) |
| PD001 | 迟早更新 |  暂无 | {{latest_content}}  |  [订阅地址](http://podcast.weareones.com/episodes/feed.xml) |
| PD001 | 随机波动 |  暂无 | {{latest_content}}  |  [订阅地址](https://feeds.fireside.fm/stovol/rss) |
| PD001 | 创业内幕|  暂无 | {{latest_content}}  |  [订阅地址](https://www.ximalaya.com/album/20119986.xml) |
| PD001 | 空无一物 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.ximalaya.com/album/40499917.xml) |
| PD001 | 硅谷101 |  暂无 | {{latest_content}}  |  [订阅地址](https://feeds.fireside.fm/sv101/rss) |
| PD001 | 翻转台电 |  暂无 | {{latest_content}}  |  [订阅地址](https://feed.xyzfm.space/36pjtvfwngyn) |
| PD001 | Manifold  |  暂无 | {{latest_content}}  |  [订阅地址](https://feeds.transistor.fm/manifold-one) |
| PD001 | 不明白播客  |  暂无 | {{latest_content}}  |  [订阅地址](https://www.bumingbai.net/feed/) | 
| <h2 id="视频">视频</h2> |  | |  | |
| VS001 | 小Lin说 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/youtube/user/@xiao_lin_shuo) |
| <h2 id="资源">资源</h2> |  | |  | |
| SS001 |  阿里云盘盘 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/yunpanpan) |
| SS001 |  阿里云盘4K影视 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/Aliyun_4K_Movies) |
| SS001 | 夸克云盘 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/kuakeyun) |
| SS001 | 每日分享频道 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/woniubuchuiniu) |
| SS001 | 黑洞资源笔记 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/piracy6) |
| SS001 | LIHAI Channel |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/lihaiba) |
| SS001 | 电子书 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/dianzhishu) |
| SS001 | ahhhhfs |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/abskoop) |
| SS001 | 油油分享频道 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/youyousharechannel) |
| SS001 | 小众软件 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.appinn.com/feed/) |
| SS001 | 不死鸟 |  暂无 | {{latest_content}}  |  [订阅地址](https://iui.su/feed/) |
| SS001 | 开源派 |  暂无 | {{latest_content}}  |  [订阅地址](https://osp.io/feed) |
| SS001 | 开源社区 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/opencfdchannel) |
| SS001 | 异次元软件 |  暂无 | {{latest_content}}  |  [订阅地址](https://feed.iplaysoft.com) |
| SS001 | 精品MAC应用分享 |  暂无 | {{latest_content}}  |  [订阅地址](http://xclient.info/feed/) |
| SS001 | Mobilism |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/mobilism/forums/android/apps) |
| SS001 | 异星软件空间 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.yxssp.com/feed) |
| SS001 | JIKE 社区 |  暂无 | {{latest_content}}  |  [订阅地址](https://jike.info/recent.rss?uid=27412&token=285b2919-5420-4c9a-8de7-9651b2f8bf1c) |

## 如何定制自己的私人简报?

从 github.com/zhaoolee/garss.git 仓库, fork一份程序到自己的仓库

允许运行actions

![允许运行actions](https://cdn.fangyuanxiaozhan.com/assets/1630216112533FANcC1QY.jpeg)

在EditREADME.md中, 展示了zhaoolee已收集的RSS列表, 你可以参考每行的格式, 按行增删自己订阅的RSS

然后按照下图设置发件邮箱相关内容即可!

![](https://cdn.fangyuanxiaozhan.com/assets/1629970189283arACkBKe.png)

在根目录, tasks.json中配置收件人, 收件人是一个对象数组, 数组中的邮箱, 都会收到邮件, 后续会扩展更多功能~

```
{
    "tasks": [
        {
            "email": "zhaoolee@gmail.com"
        },
        {
            "email": "zhaoolee@foxmail.com"
        }
    ]
}
```

设置完成后 在README.md文件的底部加个空格，并push，即可触发更新！

## 无法收到邮件怎么办

可以按照以下代码，自测一下自己的HOST, PASSWORD，USER 是否能顺利发邮件

```
!pip install yagmail

import yagmail

# 连接邮箱服务器
yag = yagmail.SMTP(user="填USER参数", password="填PASSWORD参数", host='填HOST参数')

# 邮箱正文
contents = ['今天是周末,我要学习, 学习使我快乐;', '<a href="https://www.python.org/">python官网的超链接</a>']

# 发送邮件
yag.send('填收件人邮箱', '主题:学习使我快乐', contents)
```

在线自测地址 [Colab： https://colab.research.google.com/](https://colab.research.google.com/)

![在线自测](https://i.v2ex.co/zQWM0V6b.png)

## 发送邮件的效果

![手机端优化后的邮件效果](https://cdn.fangyuanxiaozhan.com/assets/163039979740967wCT8RQ.jpeg)

![PC端优化后的邮件效果](https://cdn.fangyuanxiaozhan.com/assets/1630399693988c2tk8n7k.png)

