# Entrepreneur_Face_Detection
Developing an image classification model to detect 5 well-known entrepreneurs using labeled image.  (Jeff Bezos, Elon Musk, Jack Ma, Mark Zuckerberg, and Steve Jobs)

Here I used two approaches to identify the face detection. I used traditional machine learning approach and deep learning approach here. 

# Entrepreneur Face Detection - Traditional Machine Learning

This project uses traditional computer vision techniques to detect and recognize the faces of five well-known entrepreneurs:

- Jeff Bezos
- Mark Zuckerberg
- Jack Ma
- Steve Jobs
- Elon Musk

## 👨‍💻 Project Description

This uses OpenCV for face detection and feature extraction, followed by training multiple classical ML classifiers for face recognition. The face images are cropped using Haar cascades and preprocessed before training.

## 🧠 Techniques Used

- Face Detection using Haar Cascades
- Feature Extraction (Flattened Pixels or HOG)
- Classification using:
  - Random forest
  - Logistic regression 
  - Support Vector Machines (SVM)
- Dataset creation using OpenCV
- Face cropping based on eye detection

In here I realized, when we have images that not showing the eye properly. those images can not classify the image. 



---

#📘 Deep Learning Approach

# Entrepreneur Face Detection - Deep Learning

This version uses a Convolutional Neural Network (CNN) for face recognition of five famous entrepreneurs:

- Jeff Bezos
- Mark Zuckerberg
- Jack Ma
- Steve Jobs
- Elon Musk

## 🧠 Deep Learning Approach

- Dataset created with cropped faces using Haar cascades
- Image preprocessing and augmentation
- CNN model built with TensorFlow/Keras
- Categorical cross-entropy loss and softmax output
- Model evaluation using accuracy and confusion matrix
- models - MobileNetV2, EfficientNetB0, DenseNet121

## 🔍 Features

- End-to-end face recognition using CNN
- Data augmentation to improve generalization
- Real-time prediction capability (if integrated with camera input)

## Model comparison 
📌 DenseNet121
✅ Final Training Accuracy: 99.27%
✅ Final Test Accuracy (Validation): 85.29%

📌 EfficientNetB0
✅ Final Training Accuracy: 17.52%
✅ Final Test Accuracy (Validation): 17.65%

📌 MobileNetV2
✅ Final Training Accuracy: 99.27%
✅ Final Test Accuracy (Validation): 79.41%
