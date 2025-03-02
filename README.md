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
2. Open a terminal, navigate to the directory containing these files, and execute the script by running: python MainWindowShow.py
3. Once the script is executed, a graphical user interface (GUI) will appear, incorporating multiple functions within the panel.
4. Note: We apologize for not including the original dataset, as it is too large and restricted to private use only.
