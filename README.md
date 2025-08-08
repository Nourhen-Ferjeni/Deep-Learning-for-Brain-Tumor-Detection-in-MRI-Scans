# Deep-Learning-for-Brain-Tumor-Detection-in-MRI-Scans
# Brain Tumor Classification with CNN

## Table of Contents

1. [About the Data](#1-about-the-data)
2. [Imports & Setup](#2-imports--setup)
3. [Data Loading & Preprocessing](#3-data-loading--preprocessing)
4. [Data Visualization](#4-data-visualization)
5. [Data Processing](#5-data-processing)
6. [Optimizers](#6-optimizers)
7. [First CNN Model](#7-first-cnn-model)
8. [Pretrained CNN Model](#8-pretrained-cnn-model)
9. [Comparison of Models](#9-comparison-of-models)
10. [End of Notebook](#10-end-of-notebook)

Author: **Data Rangers**

---

## 1. About the Data

### 1.1 What is a Brain Tumor?

A brain tumor is an abnormal mass of tissue in which cells grow and multiply uncontrollably. Tumors can be either malignant (cancerous) or benign (non-cancerous). As they grow, they can increase pressure inside the skull and lead to serious health risks.

### 1.2 Why Classify Brain Tumors?

- Early detection is critical for successful treatment.
- Accurate classification helps choose the best treatment plan.
- Improves patient survival rates and quality of care.

### 1.3 Approach Used

This project uses a Convolutional Neural Network (CNN) to classify brain MRI images. Both a custom CNN and a pretrained CNN (ResNet50) are applied and compared.

---

## 2. Project Workflow

1. Train a custom CNN model on the dataset.
2. Apply transfer learning using a pretrained ResNet50.
3. Compare performance metrics (accuracy, precision, recall, F1-score).

---

## 3. About the Dataset

The dataset contains **7,023 MRI images** of the human brain, categorized into four classes:

- **Glioma**: Malignant tumors from glial cells.
- **Meningioma**: Usually benign tumors from meninges.
- **No Tumor**: Healthy brain scans.
- **Pituitary**: Tumors in the pituitary gland.

The images are sourced from multiple datasets, including **Figshare** and **Br35H**. One dataset was removed due to poor quality.

> Dataset link: [Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

---
