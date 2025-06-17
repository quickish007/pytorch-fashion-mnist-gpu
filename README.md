# Fashion MNIST - ANN (GPU Version)

This project implements an Artificial Neural Network (ANN) using PyTorch to classify images from the Fashion MNIST dataset. Unlike the earlier version trained on a CPU with a subset of 6,000 images, this version uses the **entire dataset (60,000 training images)** and is **trained on a GPU**, achieving an improved accuracy of **88%**.

## 🚀 Project Highlights

- **Framework:** PyTorch
- **Model Type:** Artificial Neural Network (ANN)
- **Dataset:** Fashion MNIST (60,000 train / 10,000 test images)
- **Training Device:** GPU
- **Accuracy Achieved:** ~88%

## 📁 Dataset Info

Fashion MNIST is a dataset of Zalando's article images — consisting of grayscale images of 10 fashion categories, such as shirts, trousers, shoes, bags, etc.

- **Training samples:** 60,000
- **Test samples:** 10,000
- **Image size:** 28x28 grayscale

## 🧠 Model Architecture

- Input Layer: 784 neurons (28x28 flattened)
- Hidden Layers: Two fully connected layers
- Activation Function: ReLU
- Output Layer: 10 neurons (Softmax for 10 classes)
- Loss Function: CrossEntropyLoss
- Optimizer: Adam

## 🖥️ Environment

- Google Colab
- Python 3.x
- PyTorch
- CUDA-enabled GPU
