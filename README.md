# Multi-Task-Learning-Framework-for-Brain-Tumor-Segmentation-and-Classification
## Overview
This project proposes a sequential multi-task learning framework for brain tumor analysis.

The segmentation model first generates tumor masks using Attention Residual U-Net. The predicted masks are then combined with the original MRI images and used as input to an InceptionV3 classifier.

## Pipeline

MRI Image

↓

Attention Residual U-Net

↓

Predicted Tumor Mask

↓

Mask + MRI Fusion

↓

InceptionV3

↓

Tumor Classification

<img width="1216" height="523" alt="MTL" src="https://github.com/user-attachments/assets/d1570de0-affd-4dc9-b056-e65ef2b78dd8" />


## Models

Segmentation:
• Attention Residual U-Net

Classification:
• InceptionV3

## Dataset

Figshare Brain Tumor MRI Dataset

## Results

Classification Accuracy:
93.23%

<img width="668" height="534" alt="cm" src="https://github.com/user-attachments/assets/04c74069-602f-493e-b73f-0d7ea90f6cb1" />


<img width="4500" height="2441" alt="predictions_vs_groundtruth (2)" src="https://github.com/user-attachments/assets/50d1e255-df95-44c3-95b9-9a4f1ea5e7dc" />


## Publication

Link to IEEE publication: [https://ieeexplore.ieee.org/abstract/document/11318534](https://ieeexplore.ieee.org/abstract/document/11318534)
