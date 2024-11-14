# Bird Species Classification: Domain-Specific Domain Adaptation

This project focuses on classifying bird species using deep learning models, emphasizing domain-specific domain adaptation. The primary objective is to train models on the **CUB-200-2011** dataset and evaluate their performance on the **Birds-525 Species** dataset. The results showcase how models adapt to new domains, providing insights into their generalization capabilities.

---

## 📂 Datasets

### 1. **CUB-200-2011 Dataset**
- **Description**: 11,788 images spanning 200 bird species with detailed annotations.
- **Usage**: Training the models.

### 2. **Birds-525 Species Dataset**
- **Description**: 84,635 training images, 2,625 test images, and 2,625 validation images from 525 bird species.
- **Usage**: Testing the generalization capability of trained models.

---

## 🎯 Objectives
1. Train deep learning models on the **CUB-200-2011** dataset.
2. Test the trained models on the **Birds-525 Species** dataset.
3. Align class names and IDs between the datasets for consistent evaluation.

---

## 🛠️ Methodology

### 1. **Model Training**
- **ResNet18**: A residual network known for effective image classification.
- **VGG16**: A deep CNN focusing on simplicity and depth.
- **MobileNetV2**: A lightweight model optimized for mobile devices.
- **Vision Transformer (ViT)**: A transformer architecture directly applied to image patches.

### 2. **Domain-Specific Domain Adaptation**
- **Class Mapping**: Aligning class names and IDs between datasets to ensure consistent evaluation.

### 3. **Evaluation Metrics**
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

---

## 📊 Results

| Model           | Training Accuracy | Validation Accuracy | Testing Accuracy | Precision | Recall | F1 Score |
|------------------|-------------------|---------------------|------------------|-----------|--------|----------|
| **ResNet18**     | 99.93%           | 87.78%             | 84.32%          | 0.86      | 0.84   | 0.84     |
| **VGG16**        | 97.82%           | 83.22%             | 80.00%          | 0.86      | 0.84   | 0.84     |
| **MobileNetV2**  | 99.89%           | 89.39%             | 85.19%          | 0.87      | 0.85   | 0.85     |
| **Vision Transformer (ViT)** | 100.00% | 97.45%             | 96.58%          | -         | -      | -        |

---

## 📝 Conclusion
This project highlights the effectiveness of deep learning models for bird species classification across different domains:
- **ResNet18**, **VGG16**, and **MobileNetV2** demonstrated robust performance metrics.
- **Vision Transformer (ViT)** outperformed others, showcasing superior domain-specific adaptation.

---

## 🚀 Future Work
1. **Hyperparameter Tuning**: Optimize parameters for improved performance.
2. **Architectural Experiments**: Explore ensemble models and novel architectures.
3. **Dataset Augmentation**: Incorporate additional bird species for comprehensive training.
4. **Real-World Applications**: Deploy models for wildlife research and conservation.

---

## 📁 Repository Structure
