---
menu_id: home
sidebar: [search, welcome, recent, timeline]
comments: false
---

{% ablock color:info %}

{% image https://cdn.jsdelivr.net/gh/SMGCDN/photos/uploads/202305152215774.png download:true fancybox:true %}

{% navbar 
[主页](/) 
[项目](/wiki/) 
[订阅](/rss/) 
[博客](https://blog.imc.re/) 
%}

{% endablock %}

# RSSBOX

五郎订阅的各种奇奇怪怪的信息流，目前正在收集东方相关信息中。。

{% link https://touhou.pub/wiki/guides/index.html desc:true %}

## Todo

- 收集东方相关信息流订阅源（长期任务）
- 收集东方相关网站，创作者等信息（长期任务）
- 编写东方相关入门介绍文档文章，制作新人引导式文档。
- 开设运维东方相关社区（待定？）
- 创建Github组织专门管理东方相关开发资源
- 妥善安排东方专属域名托管

## Logs

> 有的时候懒得手写了，可以看 [Github Commits](https://github.com/Touhou-Public/touhou-public.github.io/commits/main) 记录x

- 2023.5.19 完善[入坑指南项目](/wiki/guides/)，增加github项目合集，Awasome-Touhou等页面
- 2023.5.18 完善[入坑指南项目](/wiki/guides/)，增加新订阅源。
- 2023.5.17 创建[项目列表](/wiki)，新建[入坑指南项目](/wiki/guides/)
- 2023.5.16 丰富订阅源，增设自建RSSHub，实现网易云音乐在线播放，修改b站播放器适配问题
- 2023.5.15 更换RSSBOX订阅源为东方相关订阅源

{% ablock color:info %}

# <center>IMC.RE 讨论群</center>

{% tabs active:1 %}

<!-- tab 公告 -->

{% ablock child:iframe %}
<iframe title="dodochat" src="https://widget.imdodo.com/w/index.html#/channel?cids=1645943,1645946,1645955,1645947&iid=208930&sig=J9Mz91BVnuAX5xZ85epLOw%3D%3D&theme=1" style="border: none; width: 100%; height: 800px;"></iframe>
{% endablock %}

<!-- tab 讨论 -->

{% ablock child:iframe %}
<iframe title="dodochat" src="https://widget.imdodo.com/w/index.html#/channel?cids=1645944,1645948,1645954&iid=208930&inter=1&sig=scu6qYBK74%2BNY1XGjIE5Yg%3D%3D&theme=1" style="border: none; width: 100%; height: 800px;"></iframe>
{% endablock %}

<!-- tab Discord -->
{% ablock child:iframe %}
<iframe title="WidgetBot Discord chat embed" allow="clipboard-write" src="https://e.widgetbot.io/channels/769348161470464001/1012258700922208287?api=82547ba4-1c9a-4f26-af08-c1fe372a4bb4" style="border: none; width: 100%; height: 800px;"></iframe>
{% endablock %}

{% endtabs %}

{% endablock %}

# 其他联系方式

{% friends contact %}