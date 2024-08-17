---
layout: post
title: FlashAttention总结
date: 2024-07-13
author: 曾伟
tags: [论文阅读]
comments: true
toc: true # 目录
# pinned: true 是否置顶
---

简介：近期，看到各大公众号都在报道FlashAttention3（[报道1](https://mp.weixin.qq.com/s/62BajDjSDCCn6--tpC5ytQ)，[报道2](https://mp.weixin.qq.com/s/74-p3l8uK_kkfwVCV8o32w)，[报道3](https://mp.weixin.qq.com/s/_8kNN1s-Y3DOkv72I4U-Mg)，[报道4](https://mp.weixin.qq.com/s/0YrHdL9bEtAZpgYy2REkZw)），心想，这么牛的东西我要是能领悟其精髓，说不定也能创造厉害的东西出来，所以这个FlashAttention系列有必要好好研读一番。