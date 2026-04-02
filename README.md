# 🧠 CNN Image Classification using CIFAR-10

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify images from the CIFAR-10 dataset into 10 different categories.

---

## 📌 Project Overview
- Built a deep learning model using CNN architecture
- Trained on CIFAR-10 dataset (60,000 images)
- Achieves accurate image classification across 10 classes
- Implemented data preprocessing and normalization

---

## 🖼️ Dataset
- **CIFAR-10 Dataset**
- 60,000 images (32x32 color images)
- 10 classes:
  - Airplane ✈️
  - Automobile 🚗
  - Bird 🐦
  - Cat 🐱
  - Deer 🦌
  - Dog 🐶
  - Frog 🐸
  - Horse 🐴
  - Ship 🚢
  - Truck 🚚

📥 Dataset is automatically downloaded using `torchvision`

---

## ⚙️ Tech Stack
- Python 🐍
- PyTorch 🔥
- Torchvision
- NumPy
- Matplotlib

---

## 🧠 Model Architecture
- Convolutional Layers
- ReLU Activation
- Max Pooling
- Fully Connected Layers
- Softmax Output

---

## 🔄 Data Preprocessing
- Conversion to Tensor
- Normalization (mean = 0.5, std = 0.5)
- Batch loading using DataLoader

---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
