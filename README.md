# 🔢 Handwritten Digit Recognition Using ANN

A Deep Learning project that recognizes handwritten digits (0–9) using an Artificial Neural Network (ANN) built with TensorFlow and Keras on the MNIST dataset.

---

## 📌 Project Overview

This project focuses on image classification using Deep Learning techniques. The model is trained on the famous MNIST handwritten digit dataset and can accurately predict handwritten numbers from 0 to 9.

The main goal of this project was to understand:
- 🧠 Artificial Neural Networks (ANN)
- 🖼️ Image Classification
- ⚙️ Deep Learning workflow
- 📊 Data preprocessing and normalization
- 🤖 Model training and evaluation using TensorFlow/Keras

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| TensorFlow | Deep Learning Framework |
| Keras | Neural Network API |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Google Colab | Model Development Environment |

---

## 📂 Dataset Used

This project uses the **MNIST Handwritten Digit Dataset**.

### 📈 Dataset Details
- 🖼️ 70,000 grayscale handwritten digit images
- 🔢 Digits from 0–9
- 📏 Image size: 28×28 pixels
- 🏋️ Training Images: 60,000
- 🧪 Testing Images: 10,000

Each image contains handwritten numeric digits represented using grayscale pixel values.

---

## ✨ Features

✔️ Handwritten digit recognition system  
✔️ Image preprocessing and normalization  
✔️ ANN model implementation using TensorFlow/Keras  
✔️ Multiple Dense hidden layers  
✔️ High accuracy image classification  
✔️ Model training and evaluation workflow  
✔️ Deep Learning practical implementation  

---

## 🧠 Model Architecture

The Artificial Neural Network consists of:

1. 🔹 Flatten Layer  
2. 🔹 Dense Layer (3000 neurons, ReLU activation)  
3. 🔹 Dense Layer (1000 neurons, ReLU activation)  
4. 🔹 Output Layer (10 neurons for digit prediction)

---

## ⚙️ Project Workflow

```python
1. Import libraries
2. Load MNIST dataset
3. Visualize handwritten images
4. Normalize pixel values
5. Build ANN model
6. Compile the model
7. Train the model
8. Evaluate performance
9. Predict handwritten digits
```

---

## 📊 Training Results

| Metric | Value |
|---|---|
| 🎯 Training Accuracy | 98.95% |
| 🧪 Testing Accuracy | 97.8% |
| 📉 Test Loss | 0.0769 |

The model achieved excellent accuracy and performed well on unseen test data.

---

## 🔬 Epoch Comparison Analysis

Different epoch values were tested to observe model performance and accuracy improvement during training.

| Epochs | Accuracy | Observation |
|---|---|---|
| 2 Epochs | Lower Accuracy | Model was still learning basic digit patterns |
| 5 Epochs | Improved Accuracy | Better prediction performance observed |
| 10 Epochs | Highest Accuracy (~98.95%) | Model achieved strong learning and stable performance |

### 📌 Observation

As the number of epochs increased, the model accuracy improved and loss decreased significantly.  
Training the model for 10 epochs provided the best performance compared to lower epoch values.

This experiment helped in understanding:
- 📈 Accuracy improvement during training
- 📉 Loss reduction across epochs
- ⚙️ Impact of epochs on Deep Learning models
- 🧠 Model learning behavior

The experiment demonstrated how increasing training epochs allows the neural network to learn feature patterns more effectively from the dataset.

---

## 📚 Learning Outcomes

Through this project, I learned:

- 🧠 Neural Network fundamentals
- 🤖 TensorFlow and Keras workflow
- 📊 Data preprocessing techniques
- 📈 Accuracy and loss analysis
- 🖼️ Image classification concepts
- ⚡ Model training and evaluation
- 🔍 Deep Learning experimentation

---

## 🚀 Future Improvements

Some possible future enhancements:
- 🧠 Implement Convolutional Neural Networks (CNN)
- ⚙️ Hyperparameter tuning
- 📉 Add dropout layers to reduce overfitting
- 🌐 Deploy as a web application
- ✍️ Real-world handwritten digit prediction

---

## 🔗 Google Colab Notebook

👉 https://colab.research.google.com/drive/1YGYHCk68FYmeGFjQh9DXSBJEjddhhfrs?usp=sharing

---

## 👨‍💻 Author

**Nil Kumar Bhadani**  
B.Sc. Applied AI & Data Science  
Indian Institute of Technology Jodhpur

---

## 📜 License

This project is open-source and available for learning and educational purposes.
