# Tea Leaf Disease Classification with EfficientNetV2S

## Overview
This project focuses on classifying tea leaf diseases using EfficientNetV2S and comparing its performance with other machine learning models. Additionally, the project implements Grad-CAM for model interpretability and measures inference time for performance evaluation.

## Dataset
The dataset used in this project is sourced from Kaggle:
**[Tea Leaf Disease Dataset](https://www.kaggle.com/datasets/saikatdatta1994/tea-leaf-disease)**

The dataset consists of images of tea leaves categorized into different disease classes.

## Models Compared
- **EfficientNetV2S** (Main model)
- ResNet50
- MobileNetV3
- VGG16
- etc

## Methodology
### Preprocessing
- Image resizing
- Normalization
- Data augmentation

### Training
- Models trained using transfer learning and manual hyperparameter tunning.

### Evaluation
Metrics used include:
- Accuracy
- Precision
- Recall
- F1-score
- Loss
- ROC Curve and AUC
- Grad-CAM visualization for interpretability
- Inference time analysis
