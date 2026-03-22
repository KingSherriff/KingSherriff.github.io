---
title: "Lymph Node Cancer Detection"
excerpt: "CNN classifier for detecting the presence of cancer in lymph node histopathology images."
header:
  teaser: /assets/images/lymph-1.png
gallery:
  - url: /assets/images/lymph-1.png
    image_path: /assets/images/lymph-1.png
    alt: "Sample Data"
  - url: /assets/images/lymph-2.png
    image_path: /assets/images/lymph-2.png
    alt: "Sample Code"
tags: [Python, CNN, Computer Vision, Deep Learning, Kaggle]
---

{% include gallery layout="half" %}

## Overview
Developed a binary CNN classifier to detect cancer presence in lymph node tissue 
slides using the PatchCamelyon (PCam) dataset — a well-known Kaggle benchmark for 
medical image analysis.

## Context
PCam is a challenging real-world dataset derived from whole-slide images of lymph 
node sections. Accurate detection has direct implications for cancer staging and 
treatment planning.

## Technical Details
- **Dataset:** PatchCamelyon (PCam) — 96×96px histopathology patches
- **Task:** Binary classification — cancer present / absent
- **Architecture:** Convolutional Neural Network
- **Tools:** Python, TensorFlow/Keras, Kaggle

[View on GitHub →](https://github.com/KingSherriff/Binary-lymph-node-cancer-histology-classifier)
[View Notebook →](https://github.com/KingSherriff/Binary-lymph-node-cancer-histology-classifier/blob/main/cnn-cancer-detection-kaggle-mini-project.ipynb)