---
title: OLego
date: 2013-04-08
image: "/images/300px-OLego.png"
description: this is meta description
tags: ["splicing", "NGS", "software"]
categories: ["Application"]
author: "Jie Wu"
---

[OLego](http://zhanglab.c2b2.columbia.edu/index.php/OLego) is a program specifically designed for de novo spliced mapping of mRNA-seq reads. OLego adopts a multiple-seed-and-extend scheme and does not rely on a separate external mapper. It achieves high sensitivity of junction detection by using very small seeds (12–14 nt), efficiently mapped using the Burrows-Wheeler transform (BWT) and FM-index. This approach also makes it particularly sensitive for discovering small exons. OLego is implemented in C++ with full support for multithreading, enabling fast processing of large-scale data.

This work was published in NAR 2013. [Read the publication](http://www.ncbi.nlm.nih.gov/pubmed/23571760).