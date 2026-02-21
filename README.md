# 🎥 Deepfake Video Detection

## 🎯 Problem Statement
Deepfake videos pose serious threats to media authenticity, cybersecurity, and public trust.  
This project aims to build a machine learning system capable of identifying manipulated videos by analyzing facial frame patterns.

## 📌 Project Overview
This project implements a frame-based Convolutional Neural Network (CNN) approach for detecting deepfake videos by analyzing facial frame patterns.

---

## 🧠 Approach

1. Extract video frames using OpenCV  
2. Perform face detection  
3. Preprocess frames (resize, normalize)  
4. Train CNN model for binary classification  
5. Apply majority voting for final video-level prediction  

---

## 🛠 Tech Stack

- Python  
- OpenCV  
- TensorFlow / PyTorch  
- NumPy  
- Scikit-Learn  

---

## 📂 Project Structure
deepfake-video-detection/
│
├── data/ # Dataset (not included in repo)
├── notebooks/ # Jupyter notebooks for experiments
├── models/ # Saved trained models
├── src/ # Source code
└── README.md


---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 🚀 Future Improvements

- Add LSTM for temporal feature learning  
- Improve performance using EfficientNet  
- Deploy as a web application  
- Real-time detection system  

---

## 👤 Author

Navateja  
Machine Learning Developer
