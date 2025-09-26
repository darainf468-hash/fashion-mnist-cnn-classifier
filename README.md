
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange.svg" alt="TensorFlow Version">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</p>

# Fashion-MNIST Classifier: A Deep Dive into CNNs and Regularization

This repository contains the complete code and documentation for a Convolutional Neural Network (CNN) built from scratch to classify clothing items from the Fashion-MNIST dataset. The project was developed using TensorFlow and Keras.

More than just a simple classifier, this project focuses on implementing key regularization techniques—**Data Augmentation**, **Dropout**, and **Early Stopping**—to build a robust and well-generalized model that effectively avoids overfitting.

---

## Results & Performance

*   **Final Test Accuracy:** **90.42%** *(Achieved on the unseen test dataset)*
*   **Key Achievement:** Successfully mitigated overfitting, as shown by the close convergence of the training and validation accuracy/loss curves.

<table>
  <tr>
    <td align="center"><strong>Sample Predictions</strong></td>
    <td align="center"><strong>Model Training History</strong></td>
  </tr>
  <tr>
    <td><img src="assets/sample_predictions.png" alt="Sample Predictions"></td>
    <td><img src="assets/training_history.png" alt="Training History Plot"></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Confusion Matrix</strong></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><img src="assets/confusion_matrix.png" alt="Confusion Matrix"></td>
  </tr>
</table>

---

## Installation & Usage

To get started with this project, clone the repository and install the required dependencies.

```bash
# Clone the repository
git clone https://github.com/your-username/fashion-mnist-cnn-classifier.git

# Navigate to the project directory
cd fashion-mnist-cnn-classifier

# Install the required packages
pip install -r requirements.txt
