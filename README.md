# CIFAR-10 Image Classification

A Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify images from the CIFAR-10 dataset into 10 different categories such as airplanes, cars, birds, cats, and more. This project includes preprocessing, model training, evaluation, and performance visualization.

---

## 📌 Dataset

- **Name:** CIFAR-10
- **Size:** 60,000 color images (32x32 pixels)
- **Classes:** 
  - airplane
  - automobile
  - bird
  - cat
  - deer
  - dog
  - frog
  - horse
  - ship
  - truck

📥 Loaded directly from `tensorflow.keras.datasets`.

---

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## 🚀 How to Run

### Google Colab (Recommended)
1. Open


#  Model Architecture
Input: (32, 32, 3)
↓
Conv2D(32) + ReLU
↓
MaxPooling2D
↓
Conv2D(64) + ReLU
↓
MaxPooling2D
↓
Conv2D(128) + ReLU
↓
MaxPooling2D
↓
Flatten
↓
Dense(128) + ReLU
↓
Dropout(0.5)
↓
Dense(10) + Softmax


# Training & Validation
Optimizer: Adam

Loss Function: Categorical Crossentropy

Batch Size: 64

Epochs: 10

Validation Split: 20%

