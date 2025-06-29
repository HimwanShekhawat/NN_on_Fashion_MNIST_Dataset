# Fashion MNIST Neural Network Classifier

This project implements a custom multi-layer perceptron (MLP) neural network using NumPy to classify Fashion MNIST images. It demonstrates the end-to-end process of loading, preprocessing, training, and evaluating an image classification model without deep learning libraries.

## 📂 Features

- Load and split Fashion MNIST CSV data by class
- Normalize pixel values (zero mean, unit variance)
- One-hot encode labels
- Custom ReLU, Sigmoid, and Softmax activations
- Mini-batch gradient descent training
- Model checkpointing (best weights saved)
- Evaluation on separate test data

## 🧠 Neural Network Architecture

- Input layer: 784 nodes (28x28 pixels)
- Hidden layers: 300 and 400 neurons with ReLU activation
- Output layer: 10 classes with Softmax
- Weight initialization with He initialization
- Cross-entropy loss function

## 🚀 Training

- 600 epochs
- Batch size: 32
- Learning rate: 0.002
- Tracks training and test accuracy/cost each epoch

## 🧪 Evaluation

After training, the model is evaluated on a separate Fashion MNIST test dataset, and final accuracy and cost metrics are reported.

## 📈 Requirements

- Python 3.x
- NumPy
- Pandas
- scikit-learn
- Matplotlib

## 💡 Usage

1. Prepare the dataset CSV files.
2. Run the notebook or script.
3. Monitor training output.
4. Evaluate saved model on test data.

---

**Author:** Himwan Singh Shekhawat

Feel free to customize and extend this model for further experimentation!
