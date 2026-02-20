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

English: [PDF]({{ site.url }}/assets/attachments/articles/2013/c38a522cec683eb23b733eab305364f099f6ad8e944ec84797a2640fe85f47b1.pdf) Russian: [PDF]({{ site.url }}/assets/attachments/articles/2011/d49a6eb7eef637fb78719d5a8842b39ff443d9cc2d663bb49841c6801cfa3bc6.pdf) Russian: [PDF]({{ site.url }}/assets/attachments/articles/2012/97cd15b49e4e547c0e4ef7302db969dd3ad40962c5497b5c2d96476e8a65f76c.pdf) 

<!--more-->

## Abstract

In this paper, we consider the key-stream generator MICKEY, whose internal state splits into two parts that are updated both linearly and nonlinearly while clocking the generator. These state update functions also depend on the internal state of the registers, which perform the so-called self-mutual control. We suggest several attack scenarios based on the reverse clocking of the generator and analysis of the acquired backward states tree. Furthermore, we show meet-in-the-middle attack can be applied while simultaneously allowing the generation of shifted key streams for different pairs of keys and initialization vectors. In practice, our theoretical results are verified by extensive computations.