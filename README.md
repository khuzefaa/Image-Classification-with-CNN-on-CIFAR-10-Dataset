# Image-Classification-with-CNN-on-CIFAR-10-Dataset
 fine-tunes a Convolutional Neural Network (CNN) for scene classification using the Intel Image Classification dataset. The model is developed using the Keras Functional API, and employs advanced techniques such as EarlyStopping and Keras Tuner for hyperparameter tuning. 
# 🧠 Scene Classification Using CNNs (Part 2)

This project implements and fine-tunes a Convolutional Neural Network (CNN) using the Keras Functional API to classify scenes from the Intel Image Classification dataset. It extends the first phase of the project by introducing hyperparameter tuning, early stopping, performance visualization, and feature map exploration.

---

## 📁 Dataset

The Intel Image Classification dataset consists of six categories of natural scenes:
- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

Each image is RGB with a size of 150x150 pixels.

---

## 🛠️ Technologies Used

- Python
- TensorFlow & Keras
- Keras Tuner (for hyperparameter optimization)
- Matplotlib (for visualization)
- NumPy
- Google Colab (for training on GPU)

---

## 📌 Key Features

- ✅ Model built using Keras Functional API
- ✅ Custom architecture for scene classification
- ✅ EarlyStopping callback to prevent overfitting
- ✅ Hyperparameter tuning using `RandomSearch` from Keras Tuner
- ✅ Evaluation metrics: accuracy, loss, confusion matrix
- ✅ Visualization of training curves
- ✅ Feature map visualization of intermediate CNN layers

---

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` file.
2. Upload it to [Google Colab](https://colab.research.google.com/) or run locally if you have a compatible environment.
3. Install dependencies:
   ```bash
   pip install -U keras-tuner tensorflow
