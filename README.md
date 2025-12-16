# 🌿 Plant Leaf Disease Detection & Fertilizer Recommendation System (VGG19)

An AI-based system for **plant disease detection and fertilizer recommendation** using **VGG19 Convolutional Neural Network**, aimed at improving agricultural productivity and sustainability.

📄 **IEEE Published Research Paper**  
**Title:** Plant Disease Prediction with Fertilizer Recommendation Engine  
**Publisher:** IEEE  
🔗 https://ieeexplore.ieee.org/document/10625363

---

## 📌 Project Overview

Agriculture plays a vital role in global food security, but plant diseases significantly reduce crop yield and quality. Traditional disease detection methods are manual, time-consuming, and prone to human error.

This project proposes a **deep learning–based automated solution** that:
- Detects plant diseases from leaf images
- Uses **VGG19 CNN** for high-accuracy classification
- Provides **fertilizer and treatment recommendations**
- Helps farmers take quick and informed decisions

The system bridges the gap between **disease diagnosis and actionable solutions**, contributing to sustainable agriculture.

---

## 🎯 Objectives

- Automate plant disease detection using deep learning
- Improve accuracy compared to traditional methods
- Provide fertilizer and treatment recommendations
- Reduce dependency on agricultural experts
- Support sustainable farming practices

---

## 🧠 Technologies Used

- **Programming Language:** Python  
- **Deep Learning:** Convolutional Neural Networks (CNN)  
- **Model:** VGG19 (Transfer Learning)  
- **Frameworks:** TensorFlow, Keras  
- **Image Processing:** OpenCV  
- **Dataset:** PlantVillage, Mendeley  

---

## 🌾 Supported Crops

- Potato  
- Tomato  
- Bell Pepper  

**Disease Detection Includes:**
- Healthy leaf identification  
- Early & Late Blight  
- Leaf Mold  
- Bacterial Spot  
- Septoria Leaf Spot  

---

## 🏗️ System Architecture

1. Image Input (Leaf Image)
2. Image Preprocessing
3. Feature Extraction using VGG19
4. Disease Classification
5. Fertilizer & Treatment Recommendation
6. Output Results

---

## 📊 Model Highlights

- Uses pre-trained **VGG19** for feature extraction
- High accuracy with reduced training time
- Data augmentation to prevent overfitting
- Robust performance on real-world images

---

## 📁 Project Structure

plant-leaf-disease-detection-vgg19/
│
├── dataset/
│ ├── train/
│ ├── validation/
│
├── model/
│ └── vgg19_model.h5
│
├── notebooks/
│ └── model_training.ipynb
│
├── predict.py
├── requirements.txt
├── README.md
└── LICENSE


---
## 🌱 Future Scope

Real-time mobile application
Expansion to more crops and diseases
Integration with IoT-based smart farming
Early warning and alert systems

## ⚙️ Installation

```bash
git clone https://github.com/vipulkumar6/plant-leaf-disease-detection-vgg19.git
cd plant-leaf-disease-detection-vgg19
pip install -r requirements.txt
python predict.py --image path_to_leaf_image.jpg



