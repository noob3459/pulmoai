# 🫁 Pneumonia Detector AI

An AI-powered deep learning model that detects pneumonia from chest X-ray images using a Convolutional Neural Network (CNN). This project was developed as part of the Inspirit AI Scholars program to demonstrate how artificial intelligence can assist in medical image classification.

> 🚀 Built with TensorFlow and Python

---

## 📖 Overview

Pneumonia is a serious lung infection that can be difficult to diagnose quickly. This project uses a Convolutional Neural Network (CNN) trained on thousands of chest X-ray images to classify whether a patient has pneumonia or a normal chest X-ray.

While this model is **not intended for medical diagnosis**, it demonstrates how AI can support healthcare professionals by providing rapid image analysis.

---

## ✨ Features

- 🩻 Detects pneumonia from chest X-ray images
- 🧠 Deep learning model built with TensorFlow/Keras
- 📊 Training and validation accuracy tracking
- 📈 Loss and accuracy visualization
- 🔍 Binary image classification
- 💻 Easy-to-run Python project

---

## 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 📊 Model Performance

The model was trained for **40 epochs** using a labeled chest X-ray dataset.

**Final Results**
- ✅ Training Accuracy: **~93%**
- ✅ Validation Accuracy: **~90%**
- 📉 Validation Loss: **~0.27**

These results show the model generalizes well while maintaining high classification accuracy.

---

## 🧠 How It Works

1. Load and preprocess chest X-ray images.
2. Resize and normalize images.
3. Train a Convolutional Neural Network (CNN).
4. Validate the model on unseen images.
5. Predict whether an X-ray is:
   - Normal
   - Pneumonia

---

## 📁 Project Structure

```
├── dataset/
├── model/
├── training.ipynb
├── requirements.txt
├── README.md
└── saved_model/
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/pneumonia-detector.git
cd pneumonia-detector
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
training.ipynb
```

or run your Python script to begin training.

---

## 📸 Screenshots

Add screenshots here:

- Training Accuracy Graph
- Validation Accuracy Graph
- Loss Graph
- Example Predictions

---

## ⚠ Disclaimer

This project was created for educational and research purposes during the Inspirit AI Scholars program. It is **not** a medical device and should never replace professional medical diagnosis or treatment.

---

## 🙏 Credits

Developed by **Aidenn** as part of the **Inspirit AI Scholars Program**.

Special thanks to:
- Inspirit AI
- TensorFlow
- Keras
- The open-source medical imaging community

---

## ⭐ Future Improvements

- Improve model accuracy with transfer learning
- Build a web application for predictions
- Support additional lung diseases
- Deploy using Streamlit or Flask
- Add explainability using Grad-CAM

---

If you found this project interesting, consider giving it a ⭐ on GitHub!
