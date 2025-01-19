# Handwritten Digit Recognizer Using TensorFlow

This project implements a **handwritten digit recognition model** using the **MNIST dataset** and TensorFlow. The model uses a simple feedforward neural network to classify digits and also predicts digits from custom images using OpenCV.
## Features
- **MNIST Dataset**: Trains the model on the classic MNIST handwritten digit dataset.
- **Simple Neural Network**: A fully connected neural network with two hidden layers.
- **Model Persistence**: Save and load trained models.
- **Custom Image Predictions**: Predict handwritten digits from user-provided images using OpenCV.
- **Visualization**: Displays predictions with corresponding input images.

## Dataset
The project uses the MNIST dataset, a pre-loaded dataset in TensorFlow, which contains:
- **60,000 training examples**
- **10,000 test examples**

## Model Architecture
The neural network includes:
1. **Input Layer**: Flattens the 28x28 pixel input images into a single vector.
2. **Hidden Layers**:
   - Two dense layers with 128 neurons each and ReLU activation.
3. **Output Layer**: Dense layer with 10 neurons (one for each digit) and softmax activation.

## Training
- The model is compiled with:
  - **Optimizer**: Adam
  - **Loss**: Sparse Categorical Crossentropy
  - **Metrics**: Accuracy
- Trained for **3 epochs**.

