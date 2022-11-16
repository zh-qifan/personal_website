---
title: "使用Git的问题合集"
date: 2022-10-11
author: 张启帆
slug: note-on-git
draft: false
toc: false
categories:
  - git
tags:
  - 笔记
---

我将在这里记下使用git的时的问题。

### 1 Errno 10054
>fatal: unable to access 'https://github.com/…': OpenSSL SSL_read: Connection was reset, errno 10054
原因是因为服务器的SSL证书没有经过第三方机构的签署[^1]

解决方法为解除SSL验证：
>git config --global http.sslVerify false

[^1]: https://blog.csdn.net/weixin_44217936/article/details/124716629