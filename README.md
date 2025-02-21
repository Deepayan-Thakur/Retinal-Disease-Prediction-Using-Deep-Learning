# Retinal Disease Prediction Using Deep Learning

## 📌 Overview
This project aims to classify retinal diseases using deep learning techniques. It focuses on four categories: **normal, cataract, glaucoma, and retinal disease**. The model is trained on a structured dataset of retinal images to assist in automated diagnosis.

## 🚀 Features
- **Multi-class Classification**: Identifies whether an image belongs to one of the four categories.
- **Deep Learning Model**: Utilizes CNN-based architectures for accurate prediction.
- **Automated Image Processing**: Preprocessing techniques such as image resizing, normalization, and augmentation.
- **Performance Evaluation**: Includes metrics like accuracy, precision, recall, and confusion matrix.
- **User-Friendly Interface (Future Scope)**: Potential integration with a GUI or web-based tool.

## 📂 Dataset Structure
The dataset is structured into four subdirectories:
```bash
Dataset/
│-- 1_normal/
│-- 2_cataract/
│-- 3_glaucoma/
│-- 4_retina_disease/
```

## 🏗 Model Architecture
- Convolutional Neural Network (CNN)
- Pre-trained models like ResNet, VGG16, or EfficientNet (optional for transfer learning)
- Fully connected layers for classification
- Softmax activation for multi-class output

