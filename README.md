# Ulcerative Colitis Detection using CNN Models

This project focuses on detecting ulcerative colitis (UC) from medical images using deep learning techniques. Eleven different Convolutional Neural Network (CNN) models are implemented and compared to achieve accurate detection and classification.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Ulcerative colitis (UC) is a chronic inflammatory disease affecting the colon and rectum. Early detection and classification of UC from medical images play a crucial role in patient management and treatment planning. This project employs deep learning techniques to automatically detect and classify ulcerative colitis from endoscopic images.

## Dataset

The dataset comprises endoscopic images of patients diagnosed with ulcerative colitis. It is divided into three subsets for training, testing, and validation, ensuring a balanced distribution of positive and negative cases.

## Models

Eleven CNN models are implemented and compared for ulcerative colitis detection:

1. AlexNet
2. LeNet
3. MobileNet
4. VGG16
5. VGG19
6. Xception
7. DenseNet169
8. DenseNet121
9. DenseNet201
10. InceptionV3
11. Resnet50

Highest accuracy of 98% given by resnet50

## Evaluation Metrics

The following evaluation metrics are used to assess the performance of each model:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Receiver Operating Characteristic (ROC) curve

## Results

A comparative analysis of the performance of each model is conducted based on the evaluation metrics mentioned above. The results are presented and discussed in detail in the project report.

## Usage

To use this project:

1. Clone the repository:

```bash
git clone https://github.com/ektaghosh20/ulcerative-collitis-detection.git
