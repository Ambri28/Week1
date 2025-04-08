# Week1
Forest Fire Detection uses CNN to identify fire in forest images. Trained on labeled data, the model detects smoke or flames from satellite/drone images in real time. It helps in quick alerts, reducing damage and improving response speed.
# 🌲🔥 Forest Fire Detection using Deep Learning

## 📌 Project Overview
This project aims to detect forest fires in real-time using deep learning techniques. By analyzing satellite or drone images, the model identifies early signs of forest fires such as smoke or flames, enabling quick action and minimizing environmental damage.

## 🧠 Technology Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

## 🗃️ Dataset
We used a labeled image dataset consisting of forest areas with and without fires. The dataset was split into training and testing sets for model evaluation.

- Fire Images:  Images with visible fire/smoke  
- Non-Fire Images:  Regular forest scenes  
(Source: [Kaggle / Custom collected images])

## 🏗️ Model Architecture
We used a **Convolutional Neural Network (CNN)** with the following layers:
- Convolutional + MaxPooling layers
- Flattening layer
- Dense layers with ReLU and softmax activation
- Optimized with Adam and cross-entropy loss

## 🔍 Features
- Real-time fire detection from camera feeds or image files
- Accuracy and loss tracking using training logs
- Visualization of predictions and feature maps

## ✅ Results
- **Accuracy:** ~92% on test data
- **Precision/Recall:** High performance in fire detection scenarios
- Able to detect even subtle signs of smoke in daylight conditions

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies  
3. Run the model  

## 📦 Future Improvements
- Integrate with drone or satellite live feeds
- Add night-time infrared detection
- Deploy as a web or mobile app


