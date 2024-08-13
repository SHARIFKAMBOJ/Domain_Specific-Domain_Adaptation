# Domain_Specific And Domain_Adaptation
# Bird Species Classification: Domain-Specific Domain Adaptation
## Project Overview
This project focuses on the classification of bird species using deep learning models, particularly focusing on domain-specific domain adaptation. The primary goal is to train a model on the CUB-200-2011 dataset and test its performance on the Birds-525 Species dataset. The project evaluates the effectiveness of several models, including ResNet18, VGG16, MobileNet, and Vision Transformer, in classifying bird species, especially when applied to a domain different from the one the model was initially trained on.

## Datasets
**1. CUB-200-2011 Dataset**
- Description: The CUB-200-2011 dataset consists of 11,788 images across 200 bird species, with detailed annotations.
- Usage: Used for training the models.
**2. Birds-525 Species Dataset**
- Description: This dataset contains images from 525 bird species. It includes 84,635 training images, 2,625 test images, and 2,625 validation images.
- Usage: Used for testing the generalization capability of the trained models.
## Objectives
- Train deep learning models on the CUB-200-2011 dataset.
- Test the trained models on the Birds-525 Species dataset to evaluate domain-specific adaptation.
- Align class names and IDs between the two datasets to ensure consistency and accurate evaluation.
  
## Methodology
**1. Model Training**
- ResNet18: A residual network model known for its effectiveness in image classification tasks.
- VGG16: A deep convolutional neural network model with a focus on simplicity and depth.
- MobileNetV2: A lightweight model optimized for mobile devices, utilizing depthwise separable convolutions.
- Vision Transformer (ViT): A model architecture that applies transformers directly to image patches.

## 2. Domain-Specific Domain Adaptation
**Class Mapping:** A mapping process was implemented to standardize class names and IDs between the CUB-200-2011 and Birds-525 Species datasets, ensuring consistent evaluation.

## 3. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
## Results
**1. ResNet18**
- Training Accuracy: 99.93%
- Validation Accuracy: 87.78%
- Testing Accuracy: 84.32%
- Precision: 0.86
- Recall: 0.84
- F1 Score: 0.84
  
**2. VGG16**
- Training Accuracy: 97.82%
- Validation Accuracy: 83.22%
- Testing Accuracy: 80.00%
- Precision: 0.86
- Recall: 0.84
- F1 Score: 0.84
  
**3. MobileNetV2**
- Training Accuracy: 99.89%
- Validation Accuracy: 89.39%
- Testing Accuracy: 85.19%
- Precision: 0.87
- Recall: 0.85
- F1 Score: 0.85
  
**4. Vision Transformer (ViT)**
- Training Accuracy: 100.00%
- Validation Accuracy: 97.45%
- Testing Accuracy: 96.58%
