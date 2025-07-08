
# MNIST Digit Classifier

This project trains a deep learning model using TensorFlow and Keras to classify handwritten digits (0-9) from the MNIST dataset. It walks through the full process from data loading and preprocessing, to training, evaluation, and model export for deployment.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kEo4McU2G07MVXKnXhM47P5-oYguq8e9)

---

## 📌 Features

- ✅ Uses TensorFlow Datasets (`tfds`) to load MNIST
- ✅ Applies best practices in data preprocessing with `tf.data`
- ✅ Builds a `Sequential` Keras model with `Dense`, `Dropout`, and `ReLU`
- ✅ Evaluates model performance on a test set
- ✅ Makes predictions and visualizes the results
- ✅ Saves the trained model as `.keras` and converts it to `.tflite` for deployment

---

## 🛠️ How to Run This Notebook

1. Open this notebook in Google Colab:
   [Open in Colab](https://colab.research.google.com/drive/1kEo4McU2G07MVXKnXhM47P5-oYguq8e9)

2. Run all cells from top to bottom.

3. At the end, the model is saved locally as:
   - `mnist_classifier.keras`
   - `mnist_model.tflite`

You can download these models and deploy them to mobile, embedded systems, or continue fine-tuning.

---

## 🧠 What You’ll Learn

- How to preprocess image data efficiently with the TensorFlow `tf.data` API
- How to build and train a basic neural network using Keras
- How to evaluate model accuracy and visualize predictions
- How to export models for real-world deployment (Keras & TFLite)

---

## 📁 Files

- `mnist_classifier.ipynb` — the main training notebook
- `README.md` — this file
- `mnist_classifier.keras` — trained model (optional)
- `mnist_model.tflite` — TFLite version of the model (optional)

---

## ✅ Author

Made by Mohammad Yasen using TensorFlow 2.x and Google Colab 🚀
