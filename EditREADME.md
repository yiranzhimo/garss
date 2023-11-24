# Github Actions Rss (garss, 嘎RSS! 已收集{{rss_num}}个RSS源, 生成时间: {{ga_rss_datetime}})

信息茧房是指人们关注的信息领域会习惯性地被自己的兴趣所引导，从而将自己的生活桎梏于像蚕茧一般的“茧房”中的现象。

## 《嘎!RSS》🐣为打破信息茧房而生

![](./_media/ga-rss.png)

这个名为**嘎!RSS**的项目会利用免费的Github Actions服务, 提供一个内容全面的信息流, 让现代人的知识体系更广泛, 减弱信息茧房对现代人的影响, 让**非茧房信息流**造福人类~
[《嘎!RSS》永久开源页面: https://github.com/zhaoolee/garss](https://github.com/zhaoolee/garss)

## 推荐使用什么软件订阅RSS？
我推荐一款免费的浏览器扩展程序Feedbro ，使用教程[Chrome插件英雄榜第96期《Feedbro》在Chrome中订阅RSS信息流](https://www.v2fy.com/p/096-feedbro-2021-02-27/)

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
| PS001 | 人民日报 |  暂无 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/jingjiribao.xml) |
| PS001| 经济日报 |  暂无 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/people.xml) |
| PS001 | 南方周末 |  暂无 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/infzm.xml) |
| PS001 | 端传媒 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/theinitium_rss) |
| PS001 | 经济学人 |  暂无 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/economist.xml) |
| PS001 | 新闻联播文字版 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/cctv_news_official) |
| <h2 id="经济新闻">经济新闻</h2> |  | |  | |
| ES001 | 雷锋网|  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/leiphone) |
| ES001 | 律动 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/theblockbeats) |
| ES001 | Investing |  暂无 | {{latest_content}}  |  [订阅地址](https://feedx.net/rss/investing.xml) |
| ES001 | 新浪财经 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/sina/finance/china) |
| ES001 | Bloomberg |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/bloomberg/bbiz) |
| <h2 id="论坛">论坛</h2> |  | |  | |
| FM001 | V2EX |  暂无 | {{latest_content}}  |  [订阅地址](https://www.v2ex.com/index.xml) |
| FM001 | 雪球热帖 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/xueqiu/hots) |
| FM001 | 集思录 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/jisilu) |
| FM001 | 一亩三分地 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/1point3acres/thread/new) |
| FM001 | 虫部落 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/discuz/x/https://www.chongbuluo.com/forum.php) |
| FM001 | LessWrong |  暂无 | {{latest_content}}  |  [订阅地址](https://www.lesswrong.com/feed.xml) |
| FM001 | 吾爱破解 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.52pojie.cn/forum.php?mod=rss) |
| FM001 | 十年之约博客 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/foreverblog/feeds) |
| <h2 id="博客">博客</h2> |  | |  | |
| BS001 | 有知有行 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/youzhiyouxing/materials) |
| BS001 | 东西智库 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/dx2025) |
| BS001 | 知乎热榜 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/zhihu/hotlist) |
| BS001 | Money Orders |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/Harry_public) |
| BS001 | Financial News And Report |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/financialnews666) |
| BS001 | 你不知道的内幕消息 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/inside1024) |
| BS001 | Newlearnerの自留地 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/NewlearnerChannel) |
| BS001 | 扫地僧笔记 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/lover_links) |
| BS001 |Misso的🔋充电站 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/misso0513) |
| BS001 |Know Thyself |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/master_thyself) |
| BS001 | 小声读书 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/weekly_books) |
| BS001 | 随机漫谈 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/what_to_read_today) |
| BS001 | chatGPT中文社区 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/LptTech) |
| BS001 | ALL About RSS |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/aboutrss) |
| BS001 | 数学及其应用 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel//mathematics_and_its_applications) |
| BS001 | 书伴 |  暂无 | {{latest_content}}  |  [订阅地址](https://feeds.feedburner.com/bookfere) |
| BS001 | Aeon |  暂无 | {{latest_content}}  |  [订阅地址](https://aeon.co/feed.rss) |
| BS001 | 品葱精选 |  暂无 | {{latest_content}}  |  [订阅地址](https://project-gutenberg.github.io/Pincong/post/index.xml) |
| BS001 | 湾区日报 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/wanqu/news) |
| BS001 | 假设检验 |  暂无 | {{latest_content}}  |  [订阅地址](https://jiashejianyan.com/rss/) |
| BS001 | AIGC Weekly |  暂无 | {{latest_content}}  |  [订阅地址](https://quail.ink/op7418/feed/atom) |
| BS001 | ChinAI Newsletter |  暂无 | {{latest_content}}  |  [订阅地址](https://chinai.substack.com/feed) |
| BS001 | Big Think |  暂无 | {{latest_content}}  |  [订阅地址](https://bigthink.com/feed/all) |
| BS001 | 见字如面 |  暂无 | {{latest_content}}  |  [订阅地址](https://hiwannz.com/feed) |
| BS001 | 一方天地 |  暂无 | {{latest_content}}  |  [订阅地址](https://emmmme.com/feed.xml) |
| BS001 | 光明王 |  暂无 | {{latest_content}}  |  [订阅地址](https://lordoflight.substack.com/feed) |
| BS001 | 卢昌海的博客 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.changhai.org/index.php) |
| BS001 | MaxOS |  暂无 | {{latest_content}}  |  [订阅地址](https://maxoxo.me/rss/) |
| BS001 | 谢益辉 |  暂无 | {{latest_content}}  |  [订阅地址](https://yihui.org/index.xml) |
| BS001 | 王登科 |  暂无 | {{latest_content}}  |  [订阅地址](https://greatdk.com/feed) |
| BS001 | 扯氮集 |  暂无 | {{latest_content}}  |  [订阅地址](http://weiwuhui.com/feed) |
| BS001 | 数字游民部落 |  暂无 | {{latest_content}}  |  [订阅地址](https://jarodise.com/rss.xml) |
| BS001 | 林海草原 |  暂无 | {{latest_content}}  |  [订阅地址](https://lhcy.org/feed) |
| BS001 | 积薪 |  暂无 | {{latest_content}}  |  [订阅地址](https://firewood.news/rss.xml) |
| BS001 | 王五四文集 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/blogs/wang54) |
| BS001 | Hello Github |  暂无 | {{latest_content}}  |  [订阅地址](https://hellogithub.com/rss) |
| <h2 id="资源">资源</h2> |  | |  | |
| SS001 |  阿里云盘盘 |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/telegram/channel/yunpanpan) |
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
| SS001 | 异次元软件 |  暂无 | {{latest_content}}  |  [订阅地址](https://feed.iplaysoft.com) |
| SS001 | 精品MAC应用分享 |  暂无 | {{latest_content}}  |  [订阅地址](http://xclient.info/feed/) |
| SS001 | Mobilism |  暂无 | {{latest_content}}  |  [订阅地址](https://rsshub.app/mobilism/forums/android/apps) |
| SS001 | 异星软件空间 |  暂无 | {{latest_content}}  |  [订阅地址](https://www.yxssp.com/feed) |



## 批量导入所有RSS订阅

OPML V2.0:  [https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v2.opml](https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v2.opml) 

OPML V2.0 备用CDN地址: [https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v2.opml](https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v2.opml)



> 如果RSS软件版本较老无法识别以上订阅,请使用[V1.0版本的OPML订阅信息](https://raw.githubusercontent.com/zhaoolee/garss/main/zhaoolee_github_garss_subscription_list_v1.opml) [V1.0版本的OPML订阅信息备用CDN地址](https://cdn.jsdelivr.net/gh/zhaoolee/garss/zhaoolee_github_garss_subscription_list_v1.opml)


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

## 微信交流群

[https://frp.v2fy.com/dynamic-picture/%E5%BE%AE%E4%BF%A1%E4%BA%A4%E6%B5%81%E7%BE%A4/qr.png](https://frp.v2fy.com/dynamic-picture/%E5%BE%AE%E4%BF%A1%E4%BA%A4%E6%B5%81%E7%BE%A4/qr.png)


## 广告位招租

![广告位招租](https://raw.githubusercontent.com/zhaoolee/ChineseBQB/master/README/zhaoolee-link.png)
