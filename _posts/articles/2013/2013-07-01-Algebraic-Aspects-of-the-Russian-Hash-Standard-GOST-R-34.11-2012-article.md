---
layout: post
title: "Algebraic Aspects of the Russian Hash Standard GOST R 34.11-2012"
categories:
- algebraic attack
- hash function
- GOST r 34.11-2012
tag: article
browser_title: "Algebraic Aspects of the Russian Hash Standard GOST R 34.11-2012"
comments: true
---

English: [PDF]({{ site.url }}/assets/attachments/articles/2013/6795e47b49068629cbcb2d323faafa.pdf)

<!--more-->

## Abstract

New GOST R 34.11-2012 standard has been recently selected by the Russian government to replace the old one. The algorithm is based on the hash function Stribog introduced in 2010. The high-level structure of the new hash function is similar to GOST R 34.11-94 with minor modifications. However, the compression function was changed significantly. Such a choice of the compression algorithm has been motivated by the Rjndael due to simplicity and understandable algebraic structure.

In this paper we consider a number of algebraic aspects of the GOST R 34.11. We show how one can express the cipher in AES-like form over the finite field \\( GF(2^n) \\), and consider some approaches that can be used for the fast software implementation.