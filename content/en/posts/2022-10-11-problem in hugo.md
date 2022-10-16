---
title: "Solutions to problems in Hugo"
date: 2022-10-08
author: Qifan Zhang
slug: problem-in-hugo
draft: false
toc: false
mathjax: true
categories:
  - formal
tags:
  - article
  - English
---

I start this new page to record the problems I meet when using Hugo. I will first list them here and solve them one by one.

### 1 Alignment problem in MathJax
When I render [the page](https://zh-qifan.github.io/en/2022/10/08/why-jackknife-work/) locally, the aligned environment in Latex worked normally. But whe I published the page, all the lines in the aligned environment collapsed into one large line. This problem can be solved by using **five** backslashes which will be compiled as \\\\\ in Markdown (Why?). Is there any easy solution for this problem? 

