🧠 DeepFake Detection
📌 Overview
This repository contains the implementation of a Deepfake Detection framework using multiple machine learning and deep learning models including CNNs, ResNet, Vision Transformers (ViT), and Logistic Regression. The goal is to accurately classify manipulated facial images and videos using both spatial and global feature extraction techniques.

🔍 Problem Statement
Deepfakes pose a growing threat to digital security, misinformation, and personal privacy. This project focuses on building a robust and scalable detection system to identify manipulated media and support digital forensics.

🏗️ Model Architectures
We explored and compared the performance of the following models:

CNN: Captures local spatial patterns from images.

ResNet: Utilizes residual learning to train deep architectures effectively.

Vision Transformer (ViT): Leverages self-attention to extract global features.

Logistic Regression: Baseline model for binary classification.

📂 Datasets Used
The models were trained and tested on publicly available benchmark datasets:

FaceForensics++

Celeb-DF

Deepfake Detection Challenge (DFDC) (optional inclusion)

⚙️ Methodology
🔄 Data Preprocessing
Frame extraction from videos

Face detection and alignment

Data augmentation (rotation, flipping, color jittering)

Normalization and dataset splitting

🧪 Model Training
Custom CNN with Conv2D layers and dropout

Transfer learning with ResNet & ViT

Logistic regression using pre-extracted CNN features

Hyperparameter tuning (batch size, learning rate, dropout)

📊 Evaluation Metrics
Accuracy

Precision, Recall & F1-Score

AUC-ROC Curve

Confusion Matrix

🚀 Results

Model	Accuracy (%)
CNN	86.19
ResNet	92.68
Vision Transformer	98.11
Logistic Regression	51.05

🛠️ Technologies Used
Python

TensorFlow / Keras

PyTorch

OpenCV

Scikit-learn

Matplotlib & Seaborn

📜 Research Paper
The detailed research paper is available in this repository under Research_paper.pdf.
✅ Accepted for Oral Presentation at ICICV-2025 (Paper ID: 101)


