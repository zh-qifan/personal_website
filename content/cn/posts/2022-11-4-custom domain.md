---
title: "Github Page一直跳转到错误的域名的问题"
date: 2022-11-04
author: 张启帆
slug: wrong-custom-domain
draft: false
toc: false
categories:
  - test
tags:
  - article
---

今天在探索GitHub Page的功能时看到Custom Domain的设置，随手填了一个不存在的域名（我原以为这个可以帮我创建一个自定义的域名，后来才发现自定义域名还需另外购买。唉！对计算机网络世界一无所知！）后点了保存。结果我的个人主页开始一直跳转到那个错误的域名。
![1](/img/2022-11-04-wrong-custom-domain/wrong-custom-domain.jpg)

Google、百度了快1个小时，发现好像没有人干过这个愚蠢的事。最后，找到了[这篇关于停止使用自定义域名的文章](https://blog.csdn.net/weixin_41287260/article/details/102582315)，发现好像把浏览器的缓存清除就可以了（为什么这样做可以呢？）。后来我用IPad登上自己的网站，发现果真在其它设备上没有问题。。。
