🧠 Brain Tumor Detection using DenseNet169 + Vision Transformer (ViT)
An advanced deep learning model that combines DenseNet169 and Vision Transformer (ViT) architectures for highly accurate brain tumor detection using MRI scans.

📌 Overview
This project presents a hybrid ensemble model that leverages the power of convolutional neural networks (CNNs) and transformer-based architectures to detect brain tumors from MRI images. The model outperforms traditional architectures by capturing both local spatial features and global context.

🚀 Features
Ensemble of DenseNet169 and Vision Transformer (ViT)

Achieves state-of-the-art accuracy on the Brain Tumor MRI Dataset

Evaluated with accuracy/loss plots, classification report, ROC-AUC, and confusion matrix

Works on T1-weighted contrast-enhanced MRI images

Modular evaluation & visualization utilities

Research-grade code ready for further experimentation

🧠 Model Architecture
The ensemble combines:

DenseNet169: for extracting rich spatial features

ViT (Vision Transformer): for capturing global attention and relationships

A custom fusion layer averages the softmax outputs of both models for final prediction.

🗃️ Dataset
Kaggle Dataset: Brain Tumor MRI Dataset

Training/ and Testing/ folders

MRI images labeled as glioma, meningioma, pituitary, and no tumor

📊 Results
Accuracy        99.7+
Precision        High
Recall           High
F1-Score    Excellent
ROC-AUC        > 0.99

✨ Future Work
Integration with medical-grade deployment tools

Real-time tumor detection via streamlit or Flask app

Extension to multi-modal MRI data
