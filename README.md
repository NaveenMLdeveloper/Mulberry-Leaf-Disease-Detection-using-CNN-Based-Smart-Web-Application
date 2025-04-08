# 🍃 Mulberry Leaf Disease Detection using CNN-Based Smart Android Application

## 🎯 Objective
This project aims to develop an intelligent Android application that can automatically detect diseases in mulberry leaves using a Convolutional Neural Network (CNN). The system is designed to support farmers and agriculturists by providing **real-time diagnosis** through a mobile interface.

---

## 📂 Dataset
The dataset comprises high-resolution images of mulberry leaves classified into different disease categories. These categories include:
- 🟢 Healthy Leaves
- 🍂 Leaf Spot
- 🔴 Bacterial Blight
- 🟠 Powdery Mildew

👉 https://www.kaggle.com/datasets/nahiduzzaman13/mulberry-leaf-dataset

---

## ⚙️ Workflow Overview

### 1️⃣ Image Preprocessing
- Resize and normalize images
- Augmentation (rotation, flip, zoom) to improve generalization
- Split into training, validation, and testing sets

### 2️⃣ CNN Model Design
- Build a custom **Convolutional Neural Network**
- Use multiple layers of:
  - Convolution
  - Max Pooling
  - Dropout
  - Dense (fully connected) layers
- Compile using **categorical cross-entropy** and optimize with **Adam**

### 3️⃣ Model Training & Evaluation
- Train on the processed dataset
- Visualize **accuracy/loss curves**
- Evaluate on test set using:
  - Accuracy ✅
  - Confusion Matrix 📊
  - Classification Report 📝

🧠 **Model Accuracy Achieved**: `✅ [Please enter final test accuracy, e.g., 94.87%]`


## 🛠️ Technologies Used
- 🐍 Python
- 📦 TensorFlow / Keras
- 🖼️ OpenCV (for preprocessing)
- 📊 Matplotlib, Seaborn
- 🤖 TensorFlow Lite
- 📱 Flask

