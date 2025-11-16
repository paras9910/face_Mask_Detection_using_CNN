# face_Mask_Detection_using_CNN
A deep learning project that uses a Convolutional Neural Network (CNN) to classify whether a person is wearing a face mask or not. The model is trained on a labeled face-mask dataset and follows a complete pipeline including data loading, preprocessing, model training, and evaluation.
# 👁️ Face Detection using OpenCV

### 📊 Overview
This project implements a **Face Detection System** using **Python** and **OpenCV**, designed to automatically detect and locate human faces in images or real-time video streams.  
It demonstrates practical use of **computer vision techniques**, showing how facial features can be recognized efficiently using traditional machine learning models and pre-trained classifiers.

---

### 🎯 Objective
The goal of this project is to build a lightweight and efficient system that:
- Detects faces in static images or live camera feeds.
- Draws bounding boxes around detected faces.
- Demonstrates real-time detection using OpenCV’s Haar Cascade or DNN-based face detector.
- Acts as a foundational step toward advanced applications such as face recognition, emotion detection, or attendance systems.

---

### ⚙️ Features
- 📸 **Real-time Detection:** Works with live webcam input.  
- 🧠 **Machine Learning Model:** Uses OpenCV’s pre-trained Haar Cascade Classifier or Deep Neural Network (DNN) model.  
- ⚡ **High Speed:** Optimized for quick frame-by-frame processing.  
- 🖼️ **Multi-Face Detection:** Capable of identifying multiple faces within a single frame.  
- 💾 **Custom Input:** Accepts both image files and video sources.

---

### 🧰 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - OpenCV (cv2)  
  - NumPy  
  - Matplotlib (for image visualization)  
- **Environment:** Jupyter Notebook / VS Code  

---

### 🧠 Working Principle
1. Load the Haar Cascade or pre-trained face detection model.  
2. Convert the image to grayscale to reduce computation.  
3. Detect face regions using `detectMultiScale()` function.  
4. Draw rectangles around detected faces.  
5. Display the output image or video feed with detected faces.
