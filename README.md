# Segmentation Style Discovery: Application to Skin Lesion Images

This is the code repository for our paper published at [Medical Image Computing and Computer-Assisted Intervention (MICCAI)](https://conferences.miccai.org/2024/en/) [ISIC Skin Image Analysis Workshop (ISIC) 2024](https://workshop.isic-archive.com/2024/):

> _Segmentation Style Discovery: Application to Skin Lesion Images_<br>
> Kumar Abhishek<sup>1</sup>, Jeremy Kawahara<sup>2</sup>, Ghassan Hamarneh<sup>1</sup><br>
<sup>1</sup> Medical Image Analysis Lab, School of Computing Science, Simon Fraser University, Canada<br>
<sup>2</sup> AIP Labs, Budapest, Hungary

## Abstract

Variability in medical image segmentation, arising from annotator preferences, expertise, and their choice of tools, has been well documented. While the majority of multi-annotator segmentation approaches focus on modeling annotator-specific preferences, they require annotator-segmentation correspondence. In this work, we introduce the problem of segmentation style discovery, and propose __StyleSeg__, a segmentation method that learns plausible, diverse, and semantically consistent segmentation styles from a corpus of image-mask pairs without any knowledge of annotator correspondence. __StyleSeg__ consistently outperforms competing methods on four publicly available skin lesion segmentation (SLS) datasets. We also curate 
__ISIC-MultiAnnot__, the largest multi-annotator SLS dataset with annotator correspondence, and our results show a strong alignment, using our newly proposed measure __AS<sup>2</sup>__, between the predicted styles and annotator preferences.

## Code

--coming soon--

## ISIC-MultiAnnot Dataset

--coming soon--

## Citation

If you find our work useful or if you use one or more of the __StyleSeg__ method, the __ISIC-MultiAnnot__ dataset, and the __AS<sup>2</sup>__ measure in your work, please cite our paper: 

Kumar Abhishek, Jeremy Kawahara, Ghassan Hamarneh, "[Segmentation Style Discovery: Application to Skin Lesion Images](http://www.cs.sfu.ca/~hamarneh/ecopy/miccai_isic2024a.pdf)", Medical Image Computing and Computer-Assisted Intervention (MICCAI) ISIC Skin Image Analysis Workshop (ISIC), 2024.

The corresponding bibtex entry is:

```
@InProceedings{abhishek2024segmentation,
author = {Abhishek, Kumar and Kawahara, Jeremy and Hamarneh, Ghassan},
title = {Segmentation Style Discovery: Application to Skin Lesion Images},
booktitle = {Proceedings of the International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI) ISIC Skin Image Analysis Workshop},
month = {October},
year = {2024}
}
```
