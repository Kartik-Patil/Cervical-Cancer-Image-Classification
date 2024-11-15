# Cervical Cancer Image Classification in Deep Learning

# Link to the Web Application

Check out a GitHub repo of [Cervical Cancer Predictor](https://github.com/Dhruv195/Cervical-Cancer-Predictor)

# Overview

This repository hosts the Cervical Cancer Image Classification project, a comprehensive effort aimed at improving the classification accuracy of Squamous Cell Carcinoma (SCC) through advanced deep learning models and ensemble techniques. The project utilizes the Herlev dataset, consisting of 917 images, including both multi-cell and single-cell samples.

# Dataset Preprocessing

The dataset undergoes rigorous preprocessing to ensure quality and consistency in model training:

- Image Acquisition: Raw images are sourced from the Herlev dataset.

- Normalization: Image intensities are normalized for consistent analysis.

- Enhancement Techniques:

  - CLAHE (Contrast Limited Adaptive Histogram Equalization): Enhances image contrast.
  - Median Filter: Reduces noise and improves image clarity.
  - NLM Filter (Non-Local Means Denoising): Further enhances image quality.

- Image augmentation techniques are also applied to enrich the dataset and improve model robustness:
  - NLM Augmentation: Incorporates NLM filtering for enhanced data diversity.

# Model Training and Fine-Tuning

The project utilizes transfer learning and fine-tuning techniques to leverage pre-trained deep learning architectures, including:

- ResNet50V2
- ResNet101
- DenseNet121
- DenseNet169
- XceptionNet
- InceptionResNetV2

Transfer learning helps in enhancing the predictive capability of the models by utilizing features learned from large-scale datasets. Fine-tuning involves unfreezing the last two layers of each pre-trained model to adapt them specifically to the SCC classification task.

# Ensemble Technique

An ensemble technique is then applied to combine the strengths of individually fine-tuned models. This results in an ensemble model with an accuracy exceeding 97%. The ensemble method boosts the overall performance and robustness of the classification system.

# Results

The final model demonstrates superior classification capability, accurately distinguishing between normal and abnormal cellular images. This tool serves as a reliable aid for early detection and intervention in SCC cases, potentially making a significant impact on cancer diagnosis and patient outcomes.
