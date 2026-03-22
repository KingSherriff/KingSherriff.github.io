---
title: "Breast Cancer Histology Classifier"
excerpt: "CNN system for dual classification of breast tissue slides — benign/malignant and 8 cancer subtypes."
header:
  teaser: /assets/images/breast-1.png
gallery:
  - url: /assets/images/breast-1.png
    image_path: /assets/images/breast-1.png
    alt: "Sample Data"
  - url: /assets/images/breast-2.png
    image_path: /assets/images/breast-2.png
    alt: "Sample Code"
tags: [Python, CNN, Computer Vision, Deep Learning, PyTorch]
---

{% include gallery layout="half" %}

## Overview
Built a convolutional neural network system to assist pathologists in analyzing breast 
cancer histology slides. The model tackles two classification tasks simultaneously: 
predicting whether tissue is benign or malignant, and identifying which of eight 
specific cancer subtypes is present.

## What Makes This Interesting
Most classification tasks are binary. This project required the model to solve both 
a binary problem and an 8-class problem in parallel — a significantly harder task 
that reflects real diagnostic workflows where a pathologist needs both answers at once.

## Technical Details
- **Dataset:** BreaKHis — histopathology images at multiple zoom magnifications
- **Input:** 256×256px image patches extracted from 700×460px slides
- **Architecture:** Custom CNN with dual output heads
- **Tools:** Python, TensorFlow/Keras, NumPy, Matplotlib

## Deliverables
- `research_methodology.ipynb` — full training pipeline, EDA, and result analysis
- `demo_histology_model.ipynb` — interactive notebook to run inference on new images
- Pre-trained model weights included

[View on GitHub →](https://github.com/KingSherriff/Binary-and-Multi-label-breast-cancer-histology-classifier)
[View Notebook →](https://github.com/KingSherriff/Binary-and-Multi-label-breast-cancer-histology-classifier/blob/master/research_methodology.ipynb)