# 🫁 PulmoAI

An AI-powered web application that classifies chest X-ray images into **Healthy, Pneumonia, COVID-19, or Tuberculosis** using a deep learning model built with TensorFlow.

## 🌐 Live Demo

🚀 **Try PulmoAI here without installing anything:**

**https://disease-classifier--aidennq29.replit.app/**

Upload a chest X-ray image and receive an AI prediction in seconds.

---

## 📖 Overview

PulmoAI is a medical image classification project that demonstrates how deep learning can assist in identifying lung diseases from chest X-rays.

The model analyzes uploaded X-ray images and predicts one of four classes:

- 🟢 Healthy
- 🫁 Pneumonia
- 🦠 COVID-19
- 🔬 Tuberculosis

This project was created for educational purposes to explore the application of artificial intelligence in healthcare.

---

## ✨ Features

- Upload chest X-ray images
- AI-powered disease classification
- Four-class prediction
- Fast web interface
- TensorFlow deep learning model
- Sample X-ray dataset included
- Easy deployment

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pillow (PIL)
- Replit
- HTML / CSS / JavaScript (frontend)

---

## 🧠 AI Model

The project uses a trained Convolutional Neural Network (CNN) saved as:

```
cnn_model_lung_detection.keras
```

Class labels are stored in:

```
class_names.json
```

The model predicts one of four lung conditions from an uploaded chest X-ray image.

---

## 📂 Project Structure

```
PulmoAI/
│
├── cnn_model_lung_detection.keras
├── class_names.json
├── requirements.txt
├── sample_images/
│   ├── healthy_*.png
│   ├── pneumonia_*.png
│   ├── covid_*.png
│   └── tuberculosis_*.png
└── README.md
```

---

## 📸 Screenshots

Add screenshots here:

- 🏠 Home page
- 📤 Image upload
- 🩻 AI prediction results
- 📊 Example classifications

---

## ⚠️ Disclaimer

PulmoAI is an educational project and is **not intended to diagnose, treat, or replace professional medical advice**. Predictions should never be used as a substitute for evaluation by qualified healthcare professionals.

---

## 👨‍💻 Author

**Aidenn**

Built as an AI healthcare project demonstrating computer vision and deep learning for medical image classification.

---

## ⭐ Future Improvements

- Improve classification accuracy
- Confidence scores
- Grad-CAM visualizations
- Mobile-friendly interface
- Additional lung disease support
- Larger training dataset

---

If you found this project interesting, consider giving it a ⭐ on GitHub!
