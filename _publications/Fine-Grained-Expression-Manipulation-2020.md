---
title: "Toward Fine-grained Facial Expression Manipulation"
collection: publications
permalink: /publication/Fine-Grained-Expression-Manipulation-2020
excerpt: '**Jun Ling**, Han Xue, Li Song, Shuhui Yang, Rong Xie, Xiao Gu'
date: 2020-08-26
venue: 'ECCV'
# paperurl: 
# citation: ''
---
[pdf](https://arxiv.org/pdf/2004.03132.pdf) [code](https://github.com/junleen/Expression-manipulator)

Abstract: Facial expression manipulation aims at editing facial expression with a given condition. Previous methods edit an input image under the guidance of a discrete emotion label or absolute condition (e.g., facial action units) to possess the desired expression. However, these methods either suffer from changing condition-irrelevant regions or are inefficient for fine-grained editing. In this study, we take these two objectives into consideration and propose a novel method. First, we replace continuous absolute condition with relative condition, specifically, relative action units. With relative action units, the generator learns to only transform regions of interest which are specified by non-zero-valued relative AUs. Second, our generator is built on U-Net but strengthened by multi-scale feature fusion (MSF) mechanism for high-quality expression editing purposes. Extensive experiments on both quantitative and qualitative evaluation demonstrate the improvements of our proposed approach compared to the state-of-the-art expression editing methods.