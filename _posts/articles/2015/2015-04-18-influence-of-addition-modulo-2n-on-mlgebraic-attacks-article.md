---
layout: post
title: "Influence of Addition Modulo \\( 2^n \\) on Algebraic Attacks"
categories:
- block cipher
- algebraic attack 
- binary decision diagram
tag: article
browser_title: "Influence of Addition Modulo $2^n$ on Algebraic Attacks"
comments: true
---

English: [PDF]({{ site.url }}/assets/attachments/articles/2015/3856d196e159368deb33c7502c140d.pdf)

<!--more-->

## Abstract

Many modern ciphers have a substitution-permutation (SP) network as a main component. This design is well researched in relation to Advanced Encryption Standard (AES). One of the ways to improve the security of cryptographic primitives is the use of additional nonlinear layers. However, this replacement may not have any effect against particular cryptanalytic attacks. In this paper we use algebraic attacks to analyze an SP network with addition modulo \\( 2^n \\) as the key mixing layer. In particular, we show how to reduce the number of intermediate variables in round functions based on SP networks. We also apply the proposed method to the GOST 28147-89 block cipher that allows us to break reduced 8- and 14-round versions with complexity at most \\( 2^{155} \\) and \\( 2^{215.4} \\), respectively.