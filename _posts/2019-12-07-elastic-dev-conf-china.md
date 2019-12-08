---
layout: post
title: "Elastic 2019 中国开发者大会见闻实录"
subtitle: '好吃、好喝、还有大牛在现场~'
author: "Gangzi"
header-img: "img/post-bg-es-dev-conf.JPG"
header-mask: 0.3
tags:
  - Elastic
  - Conf
---
> 全文字数：1386个，阅读时长：约4分钟

# 大会历史
[Elastic 中国开发者大会 2018](http://conf.elasticsearch.cn/2018/shenzhen.html)（Elastic Developers China 2018）是由 Elastic 官方在中国举办的第二次开发者大会


[2019年 Elastic 中国开发者大会](http://conf.elasticsearch.cn/2019/beijing.html)（ Elastic Dev Day China 2019）再次强势回归。这是由 Elastic 官方在中国举办的第三次开发者大会


Elastic社区主旋律
分享、交流、进步、讨论、多样性、贡献

![](/img/in-post/post-es-dev-conf/blog-es-dev-conf-schedule.jpg)

# 上午
- 朱杰Elastic 
Elastic Stack 7.x的最新技术更新
官方技术人员介绍新版本的几个重要的功能和创新

- 付国庆
搜索中台，顶尖时代
听起来像是赞助商来推广自家企业的产品的
给中国解放军陆空海的做过搜索前台，实力很强大，
另外基于es搜索中台结构，下沉到开发业务层和数据接入层的中间，
数据汇交，数据治理（pipline），数据利用（包装成微服务，给各个领域、场景化主题搜索使用，search remplate）、数据共享

- medcl es中文社区活动，阿里巴巴es技术团队，阿里巴巴知识社区
es的调查报告还有es认证工程师合影，给大家树立一个榜样，非常接地气
18位最佳实践的访谈和邀请，待补图
11年写博客，留下qq群，13年线下聚会

![](/img/in-post/post-es-dev-conf/blog-es-dev-conf-medcl.jpg)



- 姜江，新东方
演讲诙谐生动
2017 splunk ，后面转型ELK
传统化转换数字化的过渡阶段
从0开始搭建docker到k8s的各个实现细节，干货满满

- 刘征，es布道师，多本书的译者
分享清晰，有吸引力，
分享的目的
开发人员，这是一门运维课：可观测性
运维人员，需要重点视角，服务监控

服务的健康检查，/health，暴露出服务的健康度（版本信息，主要修改）
 level0: 健康检查
level1: metrics
level2: 日志集中化，traceid
level3: 追踪
# 下午

下午临时有事，改为看直播，这里为大会的组织人员点赞。


分会场2-专场B：代码之美
- Elasticsearch开发进阶指南， 李捷， Elastic，解决方案架构师（售前）
初级 --> 高级
选择一个合适自己的ES版本
https://elasticsearch-benchmarks.elastic.co/#tracks/nested/release
使用Rally为自己建立基线，查看新版本对自己业务的影响是否有提升
设计篇
干货很多


# 会后

感谢Elastic中文社区组织的这次Elastic 中国技术大会2019非常成功，表现为几点：
- 参会者众多，会场爆满，还有不辞辛苦，站着聆听的参与者大有人在。
- 多数Speaker表现优异，主持人非常有激情，达到了Elastic技术大会分享和进步的目的。
- 技术Party气氛热烈，论战持久，让Gopher收获满满。
- 硬件以及组织到位，会场井然有序。
- 这次Gopher战斗服非常棒，材质很好。
- 会场的茶歇、水、水果、赞助商奖品很给力。
- 提供图文直播和在线直播服务，让没能去参加大会的技术者们可以随时观看，十分贴心。



这里对Elastic中文社区组织也表示大大的感谢！

个人也有一些小建议：
- 多些场上互动，尤其是下午场，易困倦。每个Topic分享完，可以允许提出两个问题，让大家可以参与进来，提出自己的看法。

各位讲师的slide后续还得慢慢消化，另外此次大会的相关分享链接：
- [Elasticsearch 中国开发者调查报告](https://elasticsearch.cn/article/13580)
- 大会分享PPT官方正在整理中，大家可以随时访问[elastic中文社区分享](https://elasticsearch.cn/slides/)
- [Ealstic 中国开发者大会图片直播](https://gallery.vphotos.cn/vphotosgallery/index.html?vphotowechatid=A82534CDE68C950DFD1870901F0633D5&gallery_source_code=0&toHash=&from=timeline&isappinstalled=0#/gallerypc)