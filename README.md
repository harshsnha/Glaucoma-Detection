# 🩺 Glaucoma Detection using CNN Feature Extraction with Random Forest & SVM

> 🚀 A Deep Learning and Machine Learning based approach for automated glaucoma detection using pretrained CNN feature extractors and classical ML classifiers.

---

## 📌 Project Overview

Glaucoma is one of the leading causes of irreversible blindness worldwide. Early detection can significantly reduce the risk of vision loss.

This project proposes an automated glaucoma detection system that combines the feature extraction capability of pretrained Convolutional Neural Networks (CNNs) with traditional Machine Learning classifiers such as Random Forest and Support Vector Machine (SVM).

Instead of training deep neural networks from scratch, the project utilizes transfer learning to extract meaningful image features and evaluates multiple CNN architectures to determine the best-performing model.

---

## 🎯 Objectives

- Detect glaucoma from retinal fundus images.
- Compare multiple pretrained CNN architectures.
- Evaluate Random Forest and Support Vector Machine classifiers.
- Visualize extracted features using PCA.
- Interpret CNN attention using Grad-CAM.
- Compare models using standard evaluation metrics.

---

## 🧠 CNN Feature Extractors

The following pretrained CNN models were used for feature extraction:

- ✅ EfficientNetB3
- ✅ ResNet50V2
- ✅ DenseNet121
- ✅ VGG16
- ✅ InceptionV3

---

## 🤖 Machine Learning Classifiers

The extracted features were classified using:

- 🌳 Random Forest
- 📈 Support Vector Machine (SVM)

---

## 📂 Dataset

This project uses the **EyePAC-Light v2** retinal fundus image dataset.

> **Note:** The dataset is not included in this repository due to its large size.

### Expected Dataset Structure

```
dataset/
├── train/
├── validation/
├── test/
└── metadata.csv
```

---

## 🛠️ Technologies Used

- 🐍 Python
- 🤖 TensorFlow / Keras
- 📊 Scikit-learn
- 👁️ OpenCV
- 📈 Matplotlib
- 📑 Pandas
- 🔢 NumPy
- ⚡ Jupyter Notebook

---

## 📊 Model Evaluation

The models were evaluated using:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1 Score
- ✅ ROC-AUC Score
- ✅ Confusion Matrix

Additional visualizations include:

- 📉 PCA Feature Visualization
- 🔥 Grad-CAM Heatmaps
- 📊 CNN Performance Comparison

---

## ✨ Project Highlights

- ✔ Transfer Learning based Feature Extraction
- ✔ Comparison of Five State-of-the-Art CNN Models
- ✔ Random Forest & SVM Classification
- ✔ PCA-based Feature Visualization
- ✔ Grad-CAM Explainability
- ✔ Comparative Performance Analysis

---

## 📁 Repository Structure

```
Glaucoma-Detection/
│
├── Glaucoma_Detection_CNN_RF_SVM.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 👨‍💻 Team Members

This project was developed as a **B.Tech Final Year Major Project**.

- **Harsh Sinha**
- **Dheeraj Kumar**
- **Ujjwal Raj**

---

## 🎓 Academic Information

**Institute:** Haldia Institute of Technology

**Department:** Computer Science & Engineering (AI & ML)

**Project Type:** Final Year Major Project

---

## 📌 Note

This repository contains the implementation and experimental results of our academic project.

The dataset has not been uploaded because of GitHub storage limitations.

---

## ⭐ If you found this project useful, consider giving it a Star.
