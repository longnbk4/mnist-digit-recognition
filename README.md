### MNIST-Digit-Recognition
#  MNIST Digit Recognition using Keras

This project implements a simple Convolutional Neural Network (CNN) using **Keras** to classify handwritten digits from the **MNIST dataset**.

---

## 📌 Project Overview

- **Goal**: Classify grayscale images of handwritten digits (0–9).
- **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/) – 60,000 training and 10,000 test images (28x28 pixels).
- **Framework**: TensorFlow & Keras (Python).
- **Model**: CNN with two convolutional layers + pooling + dense output.

---

##  Model Architecture

text
Input (28x28 grayscale image)
→ Conv2D (32 filters, 3x3, ReLU)
→ Conv2D (32 filters, 3x3, ReLU)
→ MaxPooling2D (2x2)
→ Dropout (0.25)
→ Flatten
→ Dense (128 units, ReLU)
→ Dropout (0.5)
→ Dense (10 units, softmax)
## How to run the code
### 1. Clone the repository
```bash
git clone https://github.com/longnbk4/mnist-digit-recognition.git
```
### 2. Install dependencies
```bash
pip install tensorflow keras matplotlib
```
### 3. Run the training script
```bash
python classification-keras.py
```
