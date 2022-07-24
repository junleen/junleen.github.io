---
title: "Region-aware Adaptive Instance Normalization for Image Harmonization"
collection: publications
permalink: /publication/2021-6-23-paper-image-harmonization-number-3
excerpt: '**Jun Ling**, Han Xue, Li Song, Rong Xie, Xiao Gu'
date: 2021-06-23
venue: 'CVPR'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
[pdf](https://openaccess.thecvf.com/content/CVPR2021/papers/Ling_Region-Aware_Adaptive_Instance_Normalization_for_Image_Harmonization_CVPR_2021_paper.pdf) [supp](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Ling_Region-Aware_Adaptive_Instance_CVPR_2021_supplemental.pdf) [code](https://github.com/junleen/RainNet)

Abstract: Image composition plays a common but important role in photo editing. To acquire photo-realistic composite images, one must adjust the appearance and visual style of the foreground to be compatible with the background. Existing deep learning methods for harmonizing composite images directly learn an image mapping network from the composite to real one, without explicit exploration on visual style consistency between the background and the foreground images. To ensure the visual style consistency between the foreground and the background, in this paper, we treat image harmonization as a style transfer problem. In particular, we propose a simple yet effective Region-aware Adaptive Instance Normalization (RAIN) module, which explicitly formulates the visual style from the background and adaptively applies them to the foreground. With our settings, our RAIN module can be used as a drop-in module for existing image harmonization networks and is able to bring significant improvements. Extensive experiments on the existing image harmonization benchmark datasets show the superior capability of the proposed method. 