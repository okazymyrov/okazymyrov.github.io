---
layout: post
title: "State Space Cryptanalysis of the MICKEY Cipher"
categories:
- MICKEY
- stream cipher
- state space
tag: article
browser_title: "State Space Cryptanalysis of the MICKEY Cipher"
comments: true
---

English: [PDF]({{ site.url }}/assets/attachments/articles/2013/13c464f5080846e6bec2988fed1d2a.pdf) Russian: [PDF]({{ site.url }}/assets/attachments/articles/2011/bfdbc6d5d3dd40484047151726008b.pdf) Russian: [PDF]({{ site.url }}/assets/attachments/articles/2012/cb2a798f82b13d640692a32579215b.pdf) 
___

<!--more-->

## Abstract

In this paper, we consider the key-stream generator MICKEY, whose internal state splits into two parts that are updated both linearly and nonlinearly while clocking the generator. These state update functions also depend on the internal state of the registers, which perform the so-called self-mutual control. We suggest several attack scenarios based on the reverse clocking of the generator and analysis of the acquired backward states tree. Furthermore, we show meet-in-the-middle attack can be applied while simultaneously allowing the generation of shifted key streams for different pairs of keys and initialization vectors. In practice, our theoretical results are verified by extensive computations.