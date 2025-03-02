# [Investigation on mold breakout prediction methods based on image recognition via convolutional neural network]

## Overview
This project develops a mold breakout prediction model using convolutional neural networks (CNNs). It employs two CNN architectures—VGG16 with transfer learning and a fine-grained MixDCNN—to distinguish true sticking regions from false ones in thermographic images. The primary goal is to identify sticking breakout samples from varied temperature patterns while filtering out normal condition samples. Ultimately, this offers a novel data-driven approach to anomaly detection in the continuous casting process. 

Link to this paer: https://link.springer.com/article/10.1007/s11663-024-03133-y

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Models](#models)
- [Results](#results)

## Installation
### Prerequisites
Before running the project, make sure you have the following dependencies installed:

- Python: version 3.6 or higher.
- Required Python package including numpy, pandas, matplotlib, sklearn etc,.
- GPU Training Dependencies: PyTorch (with a version compatible with your CUDA and cuDNN installations).

## Usage
### Running the Model 
To run the model, follow these steps:

1. Download all files from this repository and ensure they are placed within the same root directory.
2. Open a terminal, navigate to the directory containing these files, and execute the appropriate script based on the model you want to test:
To test the pre-trained VGG16 model, run: python Breakout_prediction_based_on_pretrained_VGG16.py
To test the MixDCNN model, run:, python Breakout_prediction_by_MixDCNN.py
Note: Ensure you run the code in an environment supporting your PyTorch framework, with compatible versions of CUDA and cuDNN installed.
3. Once the script executes, it will print information such as network parameters and framework details. To simplify the output, comment out the relevant print statements in the script.
5. Note: We apologize for including some output information in Chinese; we are working to provide a fully English version in future updates.

## Project Structure
│  Breakout Image Index.txt
│  Breakout_prediction_based_on_pretrained_VGG16.py
│  Breakout_prediction_by_MixDCNN.py
│          
└─南钢图像
    ├─漏钢样本
    │  ├─漏钢
    │  ├─稳态
    │  └─误报
    │ 
    └─纵裂样本
        ├─不确定
        ├─稳态  
        └─纵裂
## Models
### Model Used
