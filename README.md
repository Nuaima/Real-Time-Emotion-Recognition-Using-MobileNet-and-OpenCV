# 😊 Real-Time Emotion Recognition Using MobileNet and OpenCV

This project implements a **real-time facial emotion recognition system** using a pre-trained **MobileNet** model for feature extraction, fine-tuned with a custom dataset, and integrated with **OpenCV** for live face detection via webcam. The system classifies emotions into **7 categories**: `angry`, `disgust`, `fear`, `happy`, `sad`, `surprise`, and `neutral`.

---

## 🚀 Features
- Uses **MobileNet** (transfer learning) for lightweight and accurate classification.
- **Data augmentation** with `ImageDataGenerator` for robust training.
- Training with **early stopping** and **model checkpointing**.
- Real-time **webcam inference** with face detection (`Haar cascades`).
- Provides visualization of training accuracy/loss curves.
- Supports prediction on both **static images** and **live video**.

---

## 📂 Repository Structure
📦 Emotion-Recognition-MobileNet
├── 📄 emotion_recognition.ipynb # Jupyter/Colab notebook with training + evaluation
├── 📄 README.md # Documentation
├── 📁 dataset/ # Training and testing dataset (images by class)
│ ├── train/ # Training set
│ └── test/ # Test set
└── 📁 assets/ # Screenshots, plots, outputs


---

## 📦 Dependencies
numpy
pandas
matplotlib
tensorflow
keras
opencv-python

---
