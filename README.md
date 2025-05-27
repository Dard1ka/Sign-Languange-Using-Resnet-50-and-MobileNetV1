# Sign-Languange-Using-Resnet-50-and-MobileNetV1
🧠 Sign Language Recognition using ResNet-50 and MobileNetV1 This repository contains a deep learning-based project for recognizing sign language gestures using Convolutional Neural Networks (CNNs). The models used are ResNet-50 and MobileNetV1, chosen for their balance between accuracy and computational efficiency.

## 📂 Project Overview

- 🔍 **Model**: MobileNetV1 (from `tf.keras.applications`)
- 🖼️ **Input**: Preprocessed images of hand gestures (resized to 224x224 RGB)
- 🎯 **Output**: Prediction of sign language class (multi-class classification)
- 📚 **Framework**: TensorFlow & Keras

---

## 📁 Directory Structure

.
├── MobileNetV1
   ├── MobileNetV1.ipynb # Main notebook containing MobileNetV1 model training and evaluation
├── Resnet-50
   ├── Resnet-50.ipynb # Main notebook containing Resnet-50 model training and evaluation
├── DatasetHuruf/ # Folder for sign language dataset
   ├── Mentahan
   ├── Train
   ├── Test
   ├── Valid
└── README.md # Project documentation

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Dard1ka/Sign-Languange-Using-Resnet-50-and-MobileNetV1
cd Sign-Languange-Using-Resnet-50-and-MobileNetV1
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Dataset
We use dataset from kaggle : https://www.kaggle.com/datasets/alvinbintang/sibi-dataset

### 4. Train the Models
Open and run all cells in MobileNetV1.ipynb. The notebook handles:
- Image loading & preprocessing
- Data augmentation
- Model compilation & training
- Evaluation & visualization (accuracy, loss, classification report)

### 5. Evaluation
After training, the notebook outputs:
- Accuracy/loss plots
- Confusion matrix
- Classification report (precision, recall, F1-score)
