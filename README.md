# Customer Churn Prediction

This project predicts customer churn using a neural network built with TensorFlow and Keras. The dataset used is from a bank's credit card customers.

## 📊 Dataset
The dataset contains 10,000 entries and 14 features, such as:
- CreditScore
- Geography
- Gender
- Age
- Balance
- Number of Products
- ... and more.

## 🧠 Model Architecture
- Input layer: 11 neurons
- Hidden layer: 11 neurons (ReLU)
- Hidden layer: 11 neurons (ReLU)
- Output layer: 1 neuron (Sigmoid)

## ⚙️ Model Evaluation
- Loss Function: Binary Cross-Entropy
- Optimizer: Adam
- Epochs: 100
- Final Accuracy: **~86.6%**

## 📈 Results
- Accuracy Score: 0.8665
- Loss and Accuracy plots over epochs included

## 🛠️ Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow / keras
