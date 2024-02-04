# Skin Cancer Detection using Deep Learning

## Abstract
Cancer manifests in various forms, with melanoma being the most lethal type of skin cancer. Early detection is crucial for successful treatment. The diagnostic process involves clinical screening, dermoscopic analysis, and histopathological examination. Melanoma is highly treatable if identified early. This project focuses on automating skin cancer classification using image processing techniques.

## Problem Statement
Current skin biopsy procedures are time-consuming, taking a week or more from appointment to biopsy report. This project aims to reduce this timeline to a couple of days by implementing a predictive model based on Convolutional Neural Network (CNN) technology. This innovation has the potential to positively impact millions of lives.

## Motivation
The primary motivation behind this project is the pursuit of leveraging advanced image classification technology to contribute to the well-being of individuals. The project aligns with the progress made in computer vision through machine learning and deep learning, which can be applied across diverse domains.

## Dataset
The dataset, comprising 2357 images of malignant and benign skin diseases, is sourced from the International Skin Imaging Collaboration (ISIC). The images are categorized based on ISIC classifications. Addressing class imbalance, the Augmentor Python package is employed to augment samples across all classes.

## CNN Architecture Design
A custom CNN model is designed for skin cancer classification using skin lesion images. The architecture includes:

- Rescaling Layer: Normalizes input to [0, 1].
- Convolutional Layer: Applies convolution operations for feature extraction.
- Pooling Layer: Reduces feature map dimensions.
- Dropout Layer: Mitigates overfitting.
- Flatten Layer: Converts data into a 1D array.
- Dense Layer: Fully-connected layer for classification.
- Activation Functions (ReLU and Softmax): Enhance model learning and provide output probabilities.

This architecture enhances accuracy and performance in skin cancer classification.