---
title: "Evaluation of Multi-Modal MRI Images for Brain Tumor Segmentation"
layout: post
date: 2019-09-20 10:10
tag: jekyll
headerImage: true
projects: true
description: "My first contribution in Medical Imaging"
category: project
author: aizazsharif
tag:
- Magnetic Resonance Imaging
- Brain Tumor
- Brain Tumor Segmentation
- Deep Learning
- U-Net
externalLink: false
---

### Abstract
Brain tumors are the most threatening tumors. According to the World Health Organization (WHO) classification scheme, there are four (4) grades of brain tumors, namely, necrosis, edema, enhancing, and non-enhancing. The Magnetic Resonance Imaging (MRI) images are considered as the gold standard for capturing the contrast variations of brain tissues and are preferred due to their noninvasive nature. The four major type of MRI images that are used to detect and segment brain tumors are T1,T1c, T2 and Tf. For some tumor regions, the MRI images have very low contrast variations which make the segmentation of each grade of tumor a very difficult task. Existing models use multimodal MRI images for the segmentation of each grade of a tumor which results in downgraded performance in some tumor regions. Evaluating each MRI modality individually may improve performance in some tumor region and class. In this paper, we propose a new method that incorporates a deep learning-based model called U-Net to address the problem of brain tumor segmentation. The conceptual novelty of our method lies in modifying the U-Net model to make it suitable for multi-grade tumor segmentation task. Additionally, we use this architecture to evaluate individual MRI modalities for the segmentation of brain tumors. The proposed method is evaluated on Brain Tumor Image Segmentation (BRATS) 2015 dataset and has achieved significantly good results. It is pertinent to mention here that by using only T1 modality, we achieved the highest score for complete sub-tumoral region. On the other hand, a better result in core sub-tumoral has been achieved by using T2 modality, while the highest score in enhancing sub-tumoral region has been best achieved with the help of Tf modality

---

<center>
<img src="{{site.baseurl}}/assets/img/FlowDiagramFinal.jpg" width="700">
<figcaption class="caption">Representation of step by step processes involved in our method.</figcaption>
</center>

---
### Links for the paper 
- Submitted : [Here](http://www.icet.org.pk/2019/call-for-papers/?fbclid=IwAR13dEVoLCIKsaqvmUSp_gxAiA2CEZLRn7Bep27SllnmNH6309l1qmiCkEk)
- Dataset : <a href="https://www.smir.ch/BRATS/Start2015" download>Here</a>


