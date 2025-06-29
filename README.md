# 🗑️ Classify Waste Products Using Transfer Learning

[![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)](https://www.tensorflow.org/)

This project demonstrates the classification of waste products (organic vs. recyclable) using **Transfer Learning**. Leveraging pre-trained CNN models such as VGG16 and fine-tuning techniques, this solution is capable of distinguishing waste types to support smart waste management systems.

---

## 📌 Project Overview

This notebook is the final submission for the **IBM Skills Network course project**, focusing on **image classification** using **Transfer Learning** with TensorFlow and Keras.

### 📈 Objective

- Train a model to classify waste into two categories: **Organic (O)** and **Recyclable (R)**
- Apply transfer learning using pre-trained models
- Improve model performance via fine-tuning

---

## 🧠 Methodology

### ✔️ Tasks Covered

1. Importing Libraries and Setting Up Environment  
2. Exploratory Data Analysis on Images  
3. Data Augmentation  
4. Transfer Learning using VGG16  
5. Fine-tuning the Top Layers  
6. Model Evaluation and Metrics  
7. Saving the Trained Models  

---

## 🛠️ Tools and Libraries Used

- Python  
- TensorFlow  
- Keras  
- Matplotlib  
- NumPy  
- scikit-learn  
- Pathlib  

---

## 📁 Dataset Structure

```
/o-vs-r-split/
├── train/
│   ├── O/
│   └── R/
└── test/
    ├── O/
    └── R/
```

Each folder contains images corresponding to Organic (O) or Recyclable (R) waste categories.

---

## 🚀 Models Used

- ✅ **VGG16** as base model (with weights pre-trained on ImageNet, top layers removed)
- ✅ Fine-tuned with additional classification layers for binary classification

---

## 📊 Results

- Achieved high accuracy and generalization
- Saved models:
  - `O_R_tlearn_vgg16.keras`
  - `O_R_tlearn_fine_tune_vgg16.keras`

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/waste-classification-tl.git
cd waste-classification-tl
```

### 2. Install Dependencies

```bash
pip install tensorflow matplotlib numpy scikit-learn
```

---

## 🧪 Run the Notebook

Launch the notebook using Jupyter:

```bash
jupyter notebook "Final Proj-Classify Waste Products Using TL- FT-v1.ipynb"
```

---

## 📎 Acknowledgment

This project is part of the **IBM Skills Network** initiative and is built for educational purposes.
