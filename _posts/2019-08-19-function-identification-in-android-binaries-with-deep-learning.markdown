---
title: "Function Identification in Android Binaries with Deep Learning"
layout: post
date: 2019-09-19 12:00
tag: jekyll
headerImage: true
projects: true
description: "My Thesis research"
category: project
author: aizazsharif
tag:
- Function Identification 
- Function Boundary
- Malware Detection
- Binary Analysis
- Deep Learning
- Convolutional Neural Networks
externalLink: false
---

### Abstract
Application security support has become a preference for the enterprise as cybersecurity threats have transferred from the network perimeter to the application layer in modern years. To ensure that software is secure, organizations must test it before purchase or deployment and identify any flaws that may expose the organizations to vulnerabilities. Binary code analysis is a new method for application security testing and is transforming software security. Binary analysis aids in many important applications including automatically fixing vulnerable software and malware detection. Plenty of research has been done to improve binary analysis using datasets related to different computer platforms, new compilers, and new optimization techniques. However, there is a vast majority of Android users and since it is an open source platform it is equally vulnerable to similar attacks as well. In this research, we propose to implement deep neural networks to solve an essential yet difficult problem in binary analysis. We solve the problem of function boundary identification, a pivotal first step in a lot of binary analysis techniques. Neural networks have experienced a renewal in the past few years, achieving breakthrough outcomes in various fields such as object detection, language translation, and speech recognition. Yet no specific research has explored their utility in Android binary analysis. We exhibit that convolutional neural networks can identify functions in binaries with greater accuracy than the current state-of-the-art methods. Our model will be trained on a dataset of bytecode extracted from Android binaries. The proposed methodology is tested and evaluated on the Drebin Malware Dataset which contains Android Malware applications coming from various malware families. With the presented model, we achieved an overall precision of 0.75, recall of 0.79 and the f1 score of 0.76 in the testing phase.

---

<center>
<img src="{{site.baseurl}}/assets/img/CNNModel.jpg" class="col three caption">
<figcaption class="caption">Diagrammatic view of all the convolutions layers, filters, pooling, and connected layers of our proposed CNN architecture</figcaption>
</center>

---
### Links for the paper 
- Accepted : [Here](https://is-candar.org/)
- Download the created dataset : <a href="https://drive.google.com/open?id=1Glv-L14lE2XAfhDsPtCMV0tY7WTONJOJ" download>Here</a>

