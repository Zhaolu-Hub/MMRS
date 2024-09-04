# MMRS: Multimodal Remote Sensing Image Classification

![Figure 1: Structural diagram of the proposed MMRS in radar image classification.](https://github.com/Zhaolu-Hub/MMRS/blob/main/iamges/figure%201.png)

![Figure 2: Comparison of results from different modal algorithms on the HS-LiDAR Houston2013 dataset.](https://github.com/Zhaolu-Hub/MMRS/blob/main/iamges/figure%202.png)


## Overview
This repository contains the code for the paper titled "MMRS: Multimodal Remote Sensing Image Classification." The paper proposes a deep learning model based on multimodal fusion for remote sensing image classification. The model integrates convolutional neural networks (CNN), generative adversarial networks (GAN), and graph convolutional networks (GCN) to achieve superior classification performance on remote sensing data. 

![Figure 3: Visual comparison with and without the MFF module.](https://github.com/Zhaolu-Hub/MMRS/blob/main/iamges/figure%203.png)

## Abstract
Remote sensing image classification is a crucial task in various applications such as geographic information systems, environmental monitoring, and urban planning. Traditional methods relying on single-modal data often struggle to fully capture the complexity of surface features. In this study, we propose a deep learning model based on multimodal data fusion, which integrates optical images, radar images, and multispectral images. Our model consists of three key modules: data preprocessing and feature extraction, multimodal data generation and enhancement, and multimodal feature fusion and classification. Experimental results on the Houston2013 and HS-SAR Berlin datasets demonstrate that our model significantly outperforms existing methods in classification accuracy, robustness, and stability.

## Research Content
1. **Data Preprocessing and Feature Extraction**: Preprocess and extract features for optical, radar, and multispectral images using CNNs.
2. **Multimodal Data Generation and Enhancement**: Utilize GANs to generate and enhance multimodal data, increasing the diversity and representativeness of the dataset.
3. **Multimodal Feature Fusion and Classification**: Perform feature fusion using multi-head self-attention and GCN, followed by classification to accurately identify surface features.

### Key Features
- Combines CNN, GAN, and GCN for feature extraction, data generation, and classification.
- Incorporates multimodal data to improve classification accuracy and robustness.
- Demonstrates significant improvements over traditional single-modal methods.

## Data
The datasets used in this research can be downloaded from the following sources:
- **HS-LiDAR Houston2013 Dataset**: [Link](https://hyperspectral.ee.uh.edu/?page_id=459)
- **HS-SAR Berlin Dataset**: [Link](https://github.com/danfenghong/ISPRS_S2FL)

## How to Use

### Environment Setup
Ensure you have the necessary libraries installed by running:
```bash
pip install -r requirements.txt
