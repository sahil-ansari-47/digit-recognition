- 👋 Hi, I’m @sahil-ansari-47
- 👀 I’m interested in machine-learning, problem solving, web development, dsa
- 🌱 I’m currently learning btech electronics and communication.  
- 💞️ I’m looking to collaborate on projects on web development and image processing.
- 📫 How to reach me sahilansari28112003@gmail.com
- 😄 Pronouns: he/him

# 🧠 Handwritten Digit Recognition App

A deep learning-based application for recognizing handwritten digits using the **MNIST dataset**. Built with TensorFlow/Keras, this project uses an **Artificial Neural Network (ANN)** to classify digits with over **98% accuracy**.

---

## 📌 Features

- ✅ Trained on the popular **MNIST** dataset (70,000 labeled images of handwritten digits).
- ✅ Utilizes a **Sequential Artificial Neural Network** (ANN) model built with Keras.
- ✅ Two fully connected **hidden layers** with ReLU activation.
- ✅ **Dropout** regularization for improved generalization.
- ✅ Uses **Categorical Cross Entropy** as the loss function.
- ✅ Achieves **98.03% test accuracy** on the validation set.

---

## 🧪 Model Architecture

```python
model = Sequential([
    Flatten(input_shape=(28, 28)),
    Dense(256, activation='relu'),
    Dropout(0.5),
    Dense(40, activation='relu'),
    Dropout(0.25),
    Dense(10, activation='softmax')
])


<!---
sahil-ansari-47/sahil-ansari-47 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
