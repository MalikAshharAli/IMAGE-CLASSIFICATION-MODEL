# 🧠 Image Classification using CNN (TensorFlow)

This project demonstrates a Convolutional Neural Network (CNN) built using TensorFlow to classify images from the **CIFAR-10 dataset**, which contains 60,000 32x32 color images across 10 different categories.

---

## 📌 Project Summary

- **Framework:** TensorFlow (Keras API)
- **Dataset:** CIFAR-10
- **Model Type:** Convolutional Neural Network (CNN)
- **Task:** Image Classification
- **Output:** Trained model with test evaluation and prediction visualization

---

## 📊 Results

| Metric       | Value         |
|--------------|---------------|
| Test Accuracy (10 Epochs) | ~70% |
| Loss Function | Sparse Categorical Crossentropy |
| Optimizer     | Adam |

> 🎯 *Model performance improves with more training epochs and fine-tuning.*

---

## 🖼️ Sample Predictions

Here are sample predictions from the model on test images:

| Image | Predicted | Actual    | Correct |
|-------|-----------|-----------|---------|
| #1    | Frog      | Frog      | ✅       |
| #2    | Truck     | Truck     | ✅       |
| #3    | Airplane  | Airplane  | ✅       |
| #4    | Dog       | Dog       | ✅       |
| #5    | Bird      | Cat       | ❌       |

> ✔️ Blue label = Correct | ❌ Red label = Incorrect

---

## 📈 Accuracy Graph

The following plot shows training vs validation accuracy over 10 epochs:

```
Epoch
│
│      ▓▓▓▓▓▓ Training Accuracy
│      ░░░░░░ Validation Accuracy
│
└──────────────────────────────▶
       1   2   3 ...     10
```

---

## 📁 File Structure

```
📦 image-classification-cnn
├── Image_Classification_CNN_TensorFlow.ipynb  # Main Jupyter Notebook
├── REVIEW.md                                  # Review file (this file)
└── README.md                                  # Project overview
```

---

## ✅ How to Run

1. Install requirements:
   ```bash
   pip install tensorflow matplotlib
   ```

2. Open and run the notebook:
   ```bash
   jupyter notebook Image_Classification_CNN_TensorFlow.ipynb
   ```

3. Adjust hyperparameters as needed for performance improvement.

---

## 📌 Notes

- Dataset is automatically downloaded using Keras API.
- Model uses 3 convolutional layers followed by dense layers.
- Easily extendable to other datasets or transfer learning models.

---

## ✨ Author

**Your Name**  
B.Tech Computer Science | AI/ML Enthusiast  
[GitHub Profile](https://github.com/your-github)

---

*Feel free to fork this repo and try other datasets like Fashion-MNIST, MNIST, or even your custom images!*
