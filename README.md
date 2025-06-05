# 🧬 Skin Disease Detector

A Streamlit-based web app that uses a pre-trained CNN model to classify **8 common skin diseases** from uploaded images or webcam input.

---

## 🚀 Features

- 📸 Upload or capture images via webcam
- 🤖 Predicts 8 types of skin conditions
- 📊 Shows confidence scores
- ⚠️ Alerts for unclear predictions
- 💡 Simple UI with fast response

---

## 📁 Project Files

├── app.py # Streamlit app
├── skin_disease_model_updated.h5 # Pre-trained CNN model
├── skin_disease_model_with_opencv.ipynb # Model training/testing notebook
└── README.md

Model Details
Model: Convolutional Neural Network (CNN) MobileNetV2

Format: .h5 (Keras)

Input size: 224x224

## 🚀 Features

- 📸 Upload or capture skin images via webcam  
- 🤖 Predicts skin disease using a trained CNN (MobileNetV2)  
- 📊 Confidence score included  
- ⚠️ Warns on uncertain predictions  
- 💡 User-friendly, responsive interface  
## 🧪 Model Architecture

Model is built using **MobileNetV2** and trained on 8 skin conditions.  

[Model Architecture](images/IMG-20250424-WA0007.jpg)

---

## 🧰 Workflow

The app follows a systematic ML lifecycle from data collection to deployment:

[Workflow](images/IMG-20250424-WA0002.jpg)

---

## 📊 Evaluation

Confusion Matrix (Raw + Visual):

[Confusion Matrix](images/IMG-20250426-WA0001.jpg)  
[Confusion Matrix Heatmap](images/IMG-20250426-WA0004.jpg)
![Workflow](images/IMG-20250424-WA0002.jpg)
![Model Architecture](images/IMG-20250424-WA0007.jpg)
![Confusion Matrix](images/IMG-20250426-WA0001.jpg)
![Confusion Matrix Heatmap](images/IMG-20250426-WA0004.jpg)









