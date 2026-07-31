# 🧠 CNN Image Classifier — Handwritten Digit Recognition

A Convolutional Neural Network (CNN) built from scratch using PyTorch that recognizes
handwritten digits (0–9) with ~99% accuracy on the MNIST dataset.

## 🎯 Results
- Test Accuracy: 99%
- Dataset: MNIST (60,000 training / 10,000 testing images)
- Training Time: ~10 minutes on CPU

## 🖼️ Sample Predictions
The model correctly identifies handwritten digits in green, wrong predictions in red.

## 🏗️ Model Architecture

CNN(
conv_layers:
Conv2d(1, 32) → ReLU → MaxPool2d
Conv2d(32, 64) → ReLU → MaxPool2d
fc_layers:
Flatten → Linear(3136, 128) → ReLU → Linear(128, 10)
)

## 📊 Tech Stack
- Python 3.x
- PyTorch 2.6.0
- torchvision
- matplotlib

## 🚀 How to Run

1. Clone this repo:
   git clone https://github.com/YourUsername/cnn-mnist-classifier.git

2. Install dependencies:
   pip install torch torchvision matplotlib

3. Open the notebook:
   jupyter notebook cnn-mnist-classifier.ipynb

4. Run all cells top to bottom

## 📁 Project Structure
cnn-mnist-classifier/
├── cnn-mnist-classifier.ipynb   # Main notebook with all code
└── README.md                    # Project documentation

## 🧠 What I Learned
- How Convolutional Neural Networks process images
- Conv2d, MaxPooling, Flatten layers and their roles
- Training loop in PyTorch (forward pass, loss, backward pass)
- Evaluating model accuracy on unseen test data
- Visualizing predictions on real handwritten digits

## 👤 Author
Anubhav Choudhary
GitHub: https://github.com/YourUsername