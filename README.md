# 🧠 DeepFake Detection

📌 **Overview**  
This repository contains the implementation of a Deepfake Detection model leveraging Convolutional Neural Networks (CNNs), Vision Transformers (ViT), ResNet, and Logistic Regression. The goal is to detect manipulated facial images and videos using deep learning and traditional machine learning techniques.

---

## 🔍 Problem Statement  
Deepfakes pose a significant threat to digital security, misinformation, and privacy. This project aims to develop a robust model that can efficiently differentiate between real and fake images/videos.

---

## 🏗️ Model Architectures

- **CNN:** Captures spatial features and local patterns.
- **ResNet:** Handles deeper networks using residual connections to prevent vanishing gradients.
- **Vision Transformer (ViT):** Extracts global dependencies using self-attention mechanisms for effective feature representation.
- **Logistic Regression:** Acts as a simple baseline model for classification.

---

## 📂 Dataset

We have used publicly available deepfake datasets such as:
- **FaceForensics++**
- **Celeb-DF**

---

## ⚙️ Methodology

### 🔄 Data Preprocessing
- Face detection and alignment  
- Data augmentation (rotation, flipping, color jittering)  
- Frame extraction from videos  
- Dataset splitting (train/val/test)  

### 🧪 Model Training
- Implemented CNN, ResNet, ViT, and Logistic Regression architectures  
- Used Transfer Learning for performance enhancement  
- Fine-tuned hyperparameters (learning rate, batch size, dropout)  

### 📊 Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-Score  
- AUC-ROC Curve  

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- PyTorch  
- OpenCV  
- Scikit-learn  
- Matplotlib & Seaborn  

---

## 🚀 Results

| Model               | Accuracy (%) |
|--------------------|--------------|
| CNN                | 86.19        |
| ResNet             | 92.68        |
| Vision Transformer | 98.11        |
| Logistic Regression| 51.05        |

---

## 📜 Research Paper

The research paper detailing this work is available in the repository under **`Research_paper.pdf`**.  
✅ *Accepted for Oral Presentation at ICICV-2025* (Paper ID: 101)

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/deepfake-detection.git
cd deepfake-detection
pip install -r requirements.txt
