# 🩻 Osteoarthritis Classification Using CNN with Manual AlexNet

This medical imaging project builds a convolutional neural network (CNN) using a manually implemented AlexNet architecture to classify osteoarthritis conditions. It includes thorough exploratory analysis of the dataset and model evaluation based on classification metrics.

---

## 🔗 Dataset Access

You can download the osteoarthritis image dataset used in this project from the following link:

📁 **[Download Dataset](https://drive.google.com/file/d/1gx_UNYY6zc6RorZTSAagRQc_yZXfzBoC/view?usp=sharing)**

[![Download Dataset](https://img.shields.io/badge/Download%20Dataset-blue?style=for-the-badge)](https://drive.google.com/file/d/1gx_UNYY6zc6RorZTSAagRQc_yZXfzBoC/view?usp=sharing)

---

## 🔧 Features

- **Exploratory Data Analysis (EDA)**
  - Color histogram visualization
  - Aspect ratio distribution plot
  - Unique resolution check
  - Variability analysis across image samples
- **CNN Architecture**
  - Manually constructed AlexNet model using `tf.keras`
  - Image input pipeline via generators
  - Loss function: `sparse_categorical_crossentropy`
- **Model Evaluation**
  - Accuracy on test set
  - Detailed classification report (precision, recall, F1)
  - Confusion matrix visualization
  - Sample predictions with comparison to true labels

---

## 🧠 Concepts Used

- Convolutional Neural Networks (CNNs)
- Manual implementation of AlexNet in TensorFlow Keras
- Medical image preprocessing and augmentation
- Generator-based image batching
- Multi-class classification with sparse labels
- Evaluation using classification metrics and confusion matrix
