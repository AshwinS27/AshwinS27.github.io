---
name: "CHAOS Dataset Organ Segmentation"
tools: [Python, MRI]
description: Bioinformatics, Biomedical, CV
image: images/organ_segment.png
---
Cross sectional body images are one of the primary tools employed by medical professionals when diagnosing and assessing a patient’s condition. The accurate identification and segmentation of organs in medical images, particularly computed topography (CT) scans, is a crucial step in modern healthcare. Precise organ segmentation enables clinicians to diagnose and treat diseases more effectively, but manual segmentation is time-consuming and prone to errors. Our project aims to address this challenge by developing a machine learning solution using a U-Net architecture for organ segmentation in MRI images.

The trained U-Net model produced training and validations accuracies of 0.954 and 0.918 respectively compared to the given ground truth data in terms of measured overlapping surface area. Additionally, the relative absolute volume difference between the segmented and reference sets was 4.485% for the training set and 7.01% for the validation set.

All results, tools, and models are available on request. The python notebook used for training is available [here](https://drive.google.com/file/d/1m1QUYUA77TLax6dz50Be9sdCxOQjpCs0/view).

## Results ##
![Results](/images/organ_segment.png "result1")
