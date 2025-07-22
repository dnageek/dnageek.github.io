---
title: OLego, A Sensitive Splice Mapper
date: 2013-04-08
image: "/images/300px-OLego.png"
description: this is meta description
tags: ["splicing", "NGS", "software"]
categories: []
author: "Jie Wu"
---

[OLego](http://zhanglab.c2b2.columbia.edu/index.php/OLego) is a program specifically designed for de novo spliced mapping of mRNA-seq reads. OLego adopts a multiple-seed-and-extend scheme and does not rely on a separate external mapper. It achieves high sensitivity of junction detection by using very small seeds (12–14 nt), efficiently mapped using the Burrows-Wheeler transform (BWT) and FM-index. This approach also makes it particularly sensitive for discovering small exons. OLego is implemented in C++ with full support for multithreading, enabling fast processing of large-scale data.

- **Jie Wu**, Olga Anczuków, Adrian R. Krainer, Michael Q. Zhang, Chaolin Zhang. OLego: Fast and sensitive mapping of spliced mRNA-Seq reads using small seeds. **_Nucleic Acids Research_**, 2013, 41(10):5149-5163. **[Link](http://nar.oxfordjournals.org/content/41/10/5149)**