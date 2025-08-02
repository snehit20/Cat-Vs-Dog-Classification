# 🐱🐶 Cat vs Dog Classifier - First CNN Project

This is a Convolutional Neural Network (CNN)-based binary image classification project that classifies images of cats and dogs. It was built using TensorFlow and Keras and trained on a popular Kaggle dataset. This is my first deep learning project using CNNs, and it marks the beginning of my journey in Computer Vision and Deep Learning.

---

## 🧠 Model Overview

- **Model Type:** Convolutional Neural Network (CNN)
- **Frameworks:** TensorFlow and Keras
- **Training Accuracy:** 86.7%
- **Validation Accuracy:** 79.9%
- **Overfitting Notice:** A slight overfitting is observed, which can be reduced in future versions with better regularization and data augmentation.

---

## 📁 Dataset

- **Source:** [Dogs vs. Cats Dataset on Kaggle](https://www.kaggle.com/c/dogs-vs-cats)
- **Classes:** 2 (Cats, Dogs)
- **Total Images:** 25,000 (used subset during training for faster experimentation)

---

## 🚀 How I Trained It

The model was trained using Google Colab for ease of experimentation and GPU access. The dataset was preprocessed by resizing the images and normalizing pixel values.

Key steps:
1. Loaded and extracted the dataset from Kaggle.
2. Preprocessed and split into training and validation sets.
3. Built a CNN with multiple Conv2D and MaxPooling layers.
4. Trained using `model.fit()` with early stopping and dropout for regularization.

---

## 🛠 Tech Stack

- Python
- TensorFlow / Keras
- Google Colab
- Matplotlib / NumPy / Pandas (for EDA and visualization)

---

## 📊 Training Graphs

*Include plots if available*

---

## 📌 Learnings

- Built and trained my first CNN from scratch.
- Understood the importance of data preprocessing, overfitting, and model evaluation.
- Learned to use callbacks and dropout to handle overfitting.

---

## 🙋‍♂️ Author

**Snehit Singh**  
First CNN project - exploring the world of Computer Vision and AI.  
Feel free to check out my journey and other projects!

---

## 📄 License

This project is licensed for learning and educational purposes only.
