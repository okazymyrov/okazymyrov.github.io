---
layout: post
title: "Methods and Tools for Analysis of Symmetric Cryptographic Primitives"
categories:
- methods and tools
- cryptographic primitives
- analysis
tag: thesis
browser_title: "Methods and Tools for Analysis of Symmetric Cryptographic Primitives"
comments: true
---

English: [PDF]({{ site.url }}/assets/attachments/theses/2014/724b4abd42f31615ba01a85996c813.pdf) 
___

<!--more-->

## Abstract

The development of modern cryptography is associated with the emergence of computing machines. Since specialized equipment for protection of sensitive information was initially implemented only in hardware, stream ciphers were widespread. Later, other areas of symmetric and asymmetric cryptography were established with the invention of general-purpose processors. In particular, such symmetric cryptographic primitives as block ciphers, message authentication codes (MACs), authenticated ciphers and others began to develop rapidly. Today various cryptographic algorithms are commonly used in everyday life to protect private data.

Design and analysis of advanced symmetric cryptographic primitives require a lot of time and resources. This is related to many factors, mainly to the cryptanalysis of prospective encryption algorithms under development. Every year new and modified attacks are published, leading to a rapid increase in the quantity of requirements and criteria imposed on cryptoprimitives.

Most of this thesis is devoted to analysis and improvement of cryptographic attacks and corresponding criteria for basic components. Almost all modern cryptoprimitives use nonlinear mappings for protection against advanced attacks. In connection with that a new method was proposed for the generation of random substitutions (S-boxes) with extreme cryptographic indicators that can be used in the next-generation ciphers to provide high and ultra-high security levels. In addition, several criteria imposed on S-boxes used in block ciphers were analyzed and their significance for block ciphers was proven. It is worth mentioning a practical method of testing two vectorial Boolean functions and a universal tool for checking properties of arbitrary binary nonlinear components presented in papers gathered in this thesis.

Another part of the thesis is dedicated to the cryptanalysis of hash functions as well as block and stream ciphers. To be more precise, an algebraic attack based on a binary decision diagram (BDD) was performed on the reduced Data Encryption Standard (DES), a scaled-down version of Advanced Encryption Standard (AES) and extended affine (EA) equivalence problem. Moreover, an algebraic approach was used to reconstruct an initial representation of the current Russian hash standard GOST 34.11-2012. Finally, a backward states tree method has been used to analyze stream ciphers based on the combination principle of linear and nonlinear feedback registers.
