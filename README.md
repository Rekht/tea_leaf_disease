Tea Leaf Disease Classification with EfficientNetV2S

Overview

This project focuses on classifying tea leaf diseases using EfficientNetV2S and comparing its performance with other machine learning models. Additionally, the project implements Grad-CAM for model interpretability and measures inference time for performance evaluation.

Dataset

The dataset used in this project is sourced from Kaggle:
Tea Leaf Disease Dataset

The dataset consists of images of tea leaves categorized into different disease classes.

Models Compared

EfficientNetV2S (Main model)

ResNet50

MobileNetV3

VGG16

Random Forest (as a baseline model)

Methodology

Preprocessing: Image resizing, normalization, and data augmentation.

Training: Models trained using transfer learning and fine-tuning techniques.

Evaluation: Metrics used include:

Accuracy

Precision, Recall, and F1-score

Confusion Matrix

Grad-CAM for visualizing model attention

Inference Time to compare model efficiency

Grad-CAM Implementation

Grad-CAM (Gradient-weighted Class Activation Mapping) is used to visualize the important regions in the tea leaf images that contribute to the model's decision-making.

Results

The project compares various models based on classification performance and computational efficiency. EfficientNetV2S is expected to provide a balance between high accuracy and low inference time.

How to Run

Prerequisites

Python 3.11

TensorFlow 2.17

PyTorch (for alternative models)

OpenCV

Matplotlib

Installation

Clone the repository and install the dependencies:

git clone <repo_link>
cd <repo_folder>
pip install -r requirements.txt

Training the Model

python train.py --model efficientnetv2s --epochs 50

Running Inference

python inference.py --image sample.jpg

Running Grad-CAM

python gradcam.py --image sample.jpg

References

Kaggle Dataset: Tea Leaf Disease

Research Papers on EfficientNet and Grad-CAM

