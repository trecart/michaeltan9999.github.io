---
title: Cloudflare Email Routing的基础设置
date: 2022-03-09 14:10:00 +0800
categories: 实用技术
tags: [网络]
---

昨天除了发现Cloudflare Pages这个好东西，还在Cloudflare上面发现了一个邮件转发的功能。在这之前我是在腾讯的邮箱注册了一个组织来免费使用自定义我自己这个域名下的邮箱。总而言之呢就是虽然实现了邮件的收发功能，但是在腾讯邮箱需要填写很多的东西，而且也是需要实名注册的。但是我域名又没有在国内实名制备案，迟早会有麻烦事。相比于腾讯邮箱，这个Cloudflare的邮件转发功能就很方便了。

相较于Pages在用户第一层，这个邮件路由的功能在站点下面一层。进入之后，会自动帮你填写所需要的MX和TXT字段，待转发目的邮箱认证成功后就可以使用了。非常的快捷和方便。这样一来，我的自定义域名的邮箱便成为我常用邮箱的一个马甲名字，省去了很多在终端上面的设置。