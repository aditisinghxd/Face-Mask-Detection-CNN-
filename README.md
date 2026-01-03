# 😷 Face Mask Detection using Convolutional Neural Networks (CNN)

## 📌 Overview
This project implements a **deep learning–based face mask detection system** using **Convolutional Neural Networks (CNNs)**.  
The model classifies facial images into two categories: **with mask** and **without mask**, demonstrating the use of computer vision for real-world public safety applications.

---

## 🧠 Problem Statement
Monitoring face mask compliance manually is inefficient and error-prone.  
This project addresses the problem by leveraging **deep learning and image classification** to automatically detect mask usage in facial images.

---

## 📊 Dataset
- Image dataset consisting of facial images labeled as:
  - **With Mask**
  - **Without Mask**
- Images contain variation in lighting conditions, background, and facial orientation.

---

## ⚙️ Preprocessing Pipeline
The following preprocessing steps were applied to improve model performance:

- Grayscale conversion  
- Face bounding-box cropping  
- Image resizing to a uniform input shape  
- Pixel value normalization  

---

## 🏗 Model Architecture
- **Model Type:** Convolutional Neural Network (CNN)
- **Frameworks:** TensorFlow, Keras
- Core components:
  - Convolutional layers for feature extraction
  - Pooling layers for dimensionality reduction
  - Fully connected layers for classification
  - Binary output layer for mask / no-mask prediction

---

## 🧪 Training Details
- **Optimizer:** Adam  
- **Loss Function:** Binary Cross-Entropy  
- **Epochs:** 30  
- **Evaluation Metric:** Accuracy  

---

## ✅ Results
- Achieved **98.14% classification accuracy**
- Model successfully distinguishes masked and unmasked faces across diverse samples
- Demonstrates the effectiveness of CNNs for image-based classification tasks

---

## 🚀 Applications
- Public health compliance monitoring
- Smart surveillance systems
- Workplace and campus safety solutions
- Real-time computer vision pipelines

---

## 🛠 Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Jupyter Notebook

---

