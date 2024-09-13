---
title: Breast cancer classification
subtitle: Computer Vision
image: '/images/project-9.jpg'
---
# AI System for Breast Cancer Diagnosis

## Overview

This project, conducted in 2024, is a collaboration between our team and the Anti-Cancer Center of Sidi Bel Abbes (CAC). The objective of this project was to develop an AI system capable of diagnosing breast cancer through the classification of gigapixel hematoxylin and eosin (H&E) histopathological images (whole slide images). We used the [BRCAS](https://www.bracs.icar.cnr.it/) dataset for this purpose. The process mainly consists of two stages:

- **Feature Extraction**: This involves processing the high-resolution whole slide images to generate a more compact representation that can be processed by deep learning models.

- **Models Training**: This step involves training the actual models to classify the WSIs, using the compressed WSIs generated from the previous step as input.

The final model was deployed in a desktop application where a WSI can be selected, then the feature extraction step is applied before passing the result to the model for inference and outputting the probabilities of each class, for more details please refere to : [Github](https://github.com/Devnetly/Breast-Cancer-Detection).

![Approach](/images/approach.jpg){: width="1200" height="900"}

In addition we also developed an information system for data collection and automated patient file management. you can refer to the backend repository here: [Github](https://github.com/Devnetly/SI_CAC_BACKEND).
![Information System](/images/cac.jpg){: width="1200" height="900"}

## Technologies used 

Pytorch, OpenSlide, Tkinter, Django, ReactJS

## Role
My role in this project was developing and training state-of-the-art AI models, creating a desktop application for inference and working as a backend developer for the information system.