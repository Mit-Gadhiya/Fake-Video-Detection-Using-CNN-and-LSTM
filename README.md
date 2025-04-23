# 🎥 Fake Video Detection using CNN and LSTM

This project implements a deepfake video detection system that uses a combination of **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory (LSTM)** networks. It aims to detect manipulated videos by learning spatial and temporal features from video frames.

## 🚀 Features
- Face detection and extraction from video frames
- CNN-based spatial feature extraction
- LSTM-based temporal pattern learning
- Deepfake classification (Real vs Fake)
- Evaluation with accuracy, precision, recall, F1-score

## 🧠 Model Architecture
- **CNN**: Extracts frame-level features
- **LSTM**: Models sequence of frames to learn temporal dependencies
- Final dense layers for classification

## 🛠️ Tech Stack
- Python
- PyTorch / TensorFlow
- OpenCV
- NumPy, Pandas
- Matplotlib / Seaborn (for visualization)

## 📁 Dataset
Uses deepfake video datasets with real and fake videos. Each video is preprocessed to extract face regions for model training and testing.


