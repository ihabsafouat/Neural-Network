# CNN from Scratch with NumPy 🧠📚

This project implements a **Convolutional Neural Network (CNN)** from scratch using only **NumPy**, without relying on deep learning frameworks like TensorFlow or PyTorch. It's designed as an educational tool to understand the inner workings of CNNs layer by layer.

## 📁 Project Structure

- `CNN-Scratch.ipynb`: Jupyter notebook containing the full CNN implementation, training, and evaluation logic.

## 🧰 Features

- Convolution Layer (manually implemented)
- ReLU Activation
- Max Pooling
- Fully Connected (Dense) Layer
- Softmax Output
- Cross-Entropy Loss
- Backpropagation
- Model Training Loop with Accuracy Tracking

## 📊 Dataset

The network is trained on a simplified version of **MNIST** (likely 28x28 grayscale images). Data loading is done manually or via NumPy arrays.

> Note: Make sure you have the dataset in NumPy format (`.npy`) if it's not already included.

## 🚀 Getting Started

### Prerequisites

- Python 3.6+
- NumPy
- Jupyter Notebook (optional)

### Installation

Clone this repo:

```bash
git clone https://github.com/yourusername/cnn-from-scratch.git
cd cnn-from-scratch

```

<br/>

## 📈 Training

Training is done through a forward pass, backpropagation, and weight updates using gradient descent. Accuracy is tracked during training to monitor learning progress.

You can adjust:
- Number of epochs
- Learning rate
- Mini-batch size
- Network architecture (number of filters, layers, etc.)


## 🧪 Evaluation

After training, the model is evaluated on test data and outputs classification accuracy.


## 🧠 Learning Objectives

This project helps you understand:
- How CNNs work under the hood
- How convolutions and pooling operate
- How backpropagation is done in CNNs
- How to optimize networks without using a library


## 🙌 Acknowledgements

Inspired by:
- Stanford CS231n
- MNIST Dataset
- Deep Learning research papers and tutorials
