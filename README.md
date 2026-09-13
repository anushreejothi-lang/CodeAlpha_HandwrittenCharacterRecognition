# CodeAlpha - Handwritten Character Recognition

## 📌 Objective
Identify handwritten digits (0-9) using a Convolutional Neural Network (CNN), built as part of the CodeAlpha Machine Learning Internship (Task 3).

## 📊 Dataset
- **MNIST** dataset — 60,000 training images + 10,000 test images of handwritten digits (28x28 grayscale)

## 🧠 Model
A CNN built with TensorFlow/Keras:
- 2 Convolutional layers (32, 64 filters) + MaxPooling
- Flatten → Dense (128) → Dropout (0.3) → Dense (10, softmax)

## 📈 Results
- **Test Accuracy: 99.23%**
- **Test Loss: 0.0243**
- Confusion matrix and training curves included in the notebook
- Also tested on real handwritten digits (photos of my own handwriting) with preprocessing (thresholding, contour detection, centering)

## 🛠 Tech Stack
- Python, TensorFlow/Keras, NumPy, Matplotlib, OpenCV, Scikit-learn
- Google Colab (T4 GPU)

## 🚀 Future Scope
- Extend to EMNIST dataset for full alphabet (A-Z) character recognition
- Extend to word/sentence recognition using CRNN architecture

## 📂 Files
- `task3.ipynb` — Full notebook (data loading, preprocessing, model building, training, evaluation, custom digit testing)

## 🔗 Internship
This project is part of the **CodeAlpha Machine Learning Internship**.
