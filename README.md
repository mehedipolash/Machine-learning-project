# 🧠 Brain Tumor Detection Using Machine Learning

This repository contains the implementation and research paper for **“Brain Tumor Detection Using Machine Learning”**, developed as part of a course project at **American International University–Bangladesh (AIUB)**.  
The project applies **Convolutional Neural Networks (CNNs)** to MRI brain images to automatically detect the presence of brain tumors with high accuracy and efficiency.

---

## 📋 Overview

Brain tumor detection is a critical task in medical imaging that requires early and accurate diagnosis to improve patient outcomes.  
This research presents a **CNN-based model** capable of distinguishing between *tumor* and *non-tumor* MRI brain images.  
The model achieves an **accuracy of 89%** and an **F1-score of 0.89**, demonstrating strong potential for real-world clinical applications.

---

## 🧩 Key Features

- ✅ Machine learning-based MRI classification using **CNN**
- 📊 Achieved **89% accuracy** and **0.89 F1-score**
- 🧠 Supports early detection of brain tumors
- ⚙️ Uses **Keras (TensorFlow backend)** for implementation
- 📈 Includes performance metrics such as accuracy, precision, recall, and confusion matrix
- 💡 Designed for scalability — can be extended using **transfer learning** and **domain-specific features**

---

## 🧠 Methodology

### 1. Data Collection  
- Dataset sourced from [Kaggle – Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)  
- Total **253 MRI images**:
  - **155** with tumor  
  - **98** without tumor  

### 2. Data Preprocessing  
- Images resized to **224×224 pixels**  
- Converted to **RGB** format  
- Normalized (pixel values scaled between 0–1)  
- Labels encoded as `1` (tumor) and `0` (no tumor)

### 3. Model Architecture  
- **Convolutional + MaxPooling layers** for feature extraction  
- **Flatten + Dense layers** for classification  
- **Sigmoid activation** for binary classification  
- **Adam optimizer** and **Binary Crossentropy loss**

### 4. Evaluation Metrics  
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix Visualization  

---

## 📊 Results Summary

| Metric | Score |
|--------|--------|
| Accuracy | **89%** |
| F1-Score | **0.89** |
| True Positives | 23 |
| True Negatives | 44 |
| False Positives | 2 |
| False Negatives | 6 |

**Observations:**
- Validation accuracy remained consistent (~88–89%)  
- Training accuracy exceeded 90% after 10 epochs  
- Minimal overfitting observed after epoch 6  

---

## 🧪 Tools and Technologies

| Category | Tools/Frameworks |
|-----------|------------------|
| Programming Language | Python |
| Libraries | TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn |
| Dataset Source | Kaggle |
| IDE | Google Colab / Jupyter Notebook |

---

## 🩺 Future Improvements

- Expand dataset with more diverse MRI images  
- Implement **Transfer Learning** (e.g., VGG16, ResNet, DenseNet)  
- Integrate **domain-specific features** (tumor size, shape, location)  
- Deploy as a **web or mobile application** for clinical use  
- Optimize for **real-time predictions** on limited hardware  

---

## 👥 Authors

| Name | ID | Department | Email |
|------|----|-------------|--------|
| **Md. Mehedi Hasan Polas** | 22-46566-1 | CSE, AIUB | 22-46566-1@student.aiub.edu |
| **Sajin Mahmud Arpon** | 22-46629-1 | CSE, AIUB | 22-46629-1@student.aiub.edu |
| **Tridib Sarkar** | 22-46444-1 | CSE, AIUB | 22-46444-1@student.aiub.edu |
| **Talha Hossain Sifat** | 22-46344-1 | CSE, AIUB | 22-46344-1@student.aiub.edu |

---

## 🧾 Reference Papers

1. Patro et al., *“Brain Tumor Classification Using an Ensemble of Deep Learning Techniques”*, IEEE Access, 2024.  
2. Hassan & Boulila, *“Efficient Approach for Brain Tumor Detection Using Fuzzy Thresholding and Deep Learning”*, IEEE Access, 2025.  
3. Thokar et al., *“Medical Image Segmentation for Anomaly Detection Using Deep Learning”*, IEEE Access, 2024.  
4. Tariq et al., *“Transforming Brain Tumor Detection with Vision Transformers and EfficientNetV2”*, IEEE Access, 2025.  
5. Dataset Source – [Navoneel Chakrabarty, Kaggle Dataset (2023)](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)



If you use this work in your research, please cite it as:

