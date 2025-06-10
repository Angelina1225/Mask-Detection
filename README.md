# Mask-Detection
This project implements a **real-time face mask detection system** using **deep learning** and **computer vision** techniques. The model detects whether a person is wearing a mask or not from an image or video feed.

## 🔍 Overview

The notebook includes the following steps:
- Loading and preprocessing dataset with labeled mask/no-mask images
- Building a Convolutional Neural Network (CNN) for classification
- Training and validating the model
- Visualizing model accuracy and loss
- Performing real-time mask detection on video frames (optional)

## 🖼️ Dataset

The model uses a dataset of face images labeled as:
- With Mask 😷
- Without Mask 😐

## 🛠️ Features

- Image preprocessing with OpenCV and Keras
- CNN-based model using TensorFlow/Keras
- Accuracy and loss visualization over epochs
- Optionally supports webcam input for live mask detection

## 🚀 How to Run

You can run this notebook directly in **Google Colab**:

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `Mask_Detection.ipynb` notebook and dataset folder
3. Run the notebook cells in order to train and test the model

## 📈 Sample Output

- Plots showing training vs validation accuracy/loss
- Predictions on test images
- Optionally, real-time detection using webcam feed

## ✅ Future Improvements

- Convert model to TensorFlow Lite for mobile deployment
- Add YOLO/SSD object detection support for multiple faces
- Improve real-time performance with GPU acceleration

## 🧠 Author

**Angelina Mande**  
