# IMAGE-CLASSIFICATION-MODEL

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: MALIK ASHHAR ALI

*INTERN ID*: CT04WG141

*DOMAIN NAME*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# 🧠 Image Classification with CNN using TensorFlow

This project is a simple yet effective implementation of a **Convolutional Neural Network (CNN)** for image classification using the **CIFAR-10** dataset. It demonstrates how deep learning models can be used to recognize objects in color images.

---

## 🚀 Features

- ✅ Built using **TensorFlow (Keras)**
- 📊 Trained and evaluated on **CIFAR-10**, a standard 10-class image dataset
- 📈 Includes **training & validation accuracy graphs**
- 🧪 Shows predictions and confidence for sample images
- 📁 Clean and organized Jupyter notebook

---

## 🗂️ Dataset: CIFAR-10

- **Images:** 60,000 color images (32x32 pixels)
- **Classes:** 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- **Split:** 50,000 for training and 10,000 for testing

---

## 🧱 CNN Architecture

- 3 Convolutional Layers with ReLU Activation
- Max Pooling after each Conv Layer
- Fully Connected Dense Layers
- Output Layer with 10 Classes (Softmax)

---

## 📊 Model Performance

- **Test Accuracy:** ~70% (after 10 epochs)
- Can be improved further with:
  - Data Augmentation
  - More Layers
  - Dropout or Batch Normalization

---

## 🖥️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-github/image-classification-cnn.git
Install dependencies:

bash
Copy
Edit
pip install tensorflow matplotlib
Run the notebook:

bash
Copy
Edit
jupyter notebook Image_Classification_CNN_TensorFlow.ipynb
📦 File Overview
bash
Copy
Edit
📦 image-classification-cnn
├── Image_Classification_CNN_TensorFlow.ipynb  # Main model and training
├── REVIEW.md                                  # Project showcase and review
└── README.md                                  # Project description and setup
