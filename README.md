# 📸 CIFAR-10 Image Classification using CNN

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

---

## 📌 Project Overview

This project uses a **Convolutional Neural Network (CNN)** trained on the **CIFAR-10 dataset** to classify images into one of ten object categories. The model is deployed through an interactive **Streamlit web application**, allowing users to upload images and receive real-time predictions with confidence scores.

---

## 🎯 Objectives

* Build an image classification model using CNNs
* Train on the CIFAR-10 benchmark dataset
* Deploy the trained model using Streamlit
* Predict uploaded images in real time
* Visualize prediction probabilities for all classes

---

## 🧠 CIFAR-10 Classes

The model classifies images into the following categories:

| Class         |
| ------------- |
| ✈ Airplane    |
| 🚗 Automobile |
| 🐦 Bird       |
| 🐱 Cat        |
| 🦌 Deer       |
| 🐶 Dog        |
| 🐸 Frog       |
| 🚢 Ship       |
| 🚚 Truck      |
| 🐠 Fish       |

---

## ⚙️ How It Works

### 1. Image Upload

Users upload an image in one of the supported formats:

* JPG
* JPEG
* PNG

### 2. Preprocessing

The uploaded image is:

* Converted to RGB format
* Resized to 32 × 32 pixels
* Normalized to values between 0 and 1
* Converted into a tensor suitable for CNN input

### 3. Prediction

The trained CNN model predicts:

* Most likely class
* Confidence score (%)
* Probability distribution across all classes

---

## 🚀 Features

* 📂 Upload custom images
* 🤖 CNN-based image classification
* ⚡ Real-time predictions
* 📊 Probability visualization using charts
* 🎨 Clean Streamlit interface
* 📱 Responsive dashboard

---

## 🛠️ Tech Stack

| Technology         | Purpose                   |
| ------------------ | ------------------------- |
| Python             | Programming Language      |
| TensorFlow / Keras | Deep Learning Framework   |
| NumPy              | Numerical Operations      |
| Pillow (PIL)       | Image Processing          |
| Streamlit          | Web Application Framework |

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/cifar10-image-classifier.git
cd cifar10-image-classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Then open:

```text
http://localhost:8501
```

---

## 📂 Project Structure

```text
CIFAR10_Image_Classifier/
│
├── app.py                   # Streamlit application
├── cifar10_cnn_model.h5     # Trained CNN model
├── requirements.txt         # Dependencies
├── README.md                # Documentation
└── sample_images/           # Example images (optional)
```

---

## 📊 Model Workflow

```text
Input Image
     ↓
Resize (32x32)
     ↓
Normalization
     ↓
CNN Model
     ↓
Softmax Output
     ↓
Class Prediction
     ↓
Confidence Score
```

---

## 📈 Output Example

### Uploaded Image

🐶 Dog

### Prediction

```text
Class: 🐶 Dog
Confidence: 98.74%
```

The application also displays prediction probabilities for all CIFAR-10 classes using a bar chart.

---

## 🔮 Future Improvements

* Add Grad-CAM visualizations
* Support batch image predictions
* Deploy on Streamlit Cloud
* Compare multiple CNN architectures
* Add top-3 prediction results

---

## 🎓 Learning Outcomes

* Deep Learning with CNNs
* Image Classification
* TensorFlow/Keras Model Deployment
* Streamlit Dashboard Development
* Image Preprocessing Techniques

---

## ⭐ Author

Developed as a Deep Learning and Computer Vision project using TensorFlow, Keras, and Streamlit.
