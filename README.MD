# MNIST Handwritten Digit Recognition

## Project Overview

This project focuses on developing a handwritten digit recognition system using Deep Learning. It uses the **MNIST dataset**, a widely used collection of handwritten digits, to train an Artificial Neural Network (ANN) capable of classifying images into one of ten categories (0–9).

The project covers the main stages of a machine learning workflow, from data preparation and model training to evaluation and practical implementation through a graphical user interface.

## Objectives

- Understand and implement a Deep Learning classification model.
- Work with image data and prepare it for model training.
- Build and train an Artificial Neural Network.
- Evaluate the model's performance using classification metrics.
- Integrate the trained model into a graphical application for interactive predictions.

## Dataset

The project uses the **MNIST dataset**, which contains:

- 70,000 grayscale images of handwritten digits.
- 60,000 training images.
- 10,000 testing images.
- Image dimensions of 28 × 28 pixels.
- Ten possible classes, representing digits from 0 to 9.

Each image is represented by pixel intensity values ranging from 0 to 255.

## Technologies and Libraries

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| TensorFlow / Keras | Building and training the neural network |
| NumPy | Numerical computations and array manipulation |
| Matplotlib | Data visualization and plotting |
| Pandas | Data manipulation |
| Tkinter | Graphical user interface |
| Pillow | Image processing |
| Jupyter Notebook | Model development and experimentation |

## Project Workflow

### 1. Data Loading and Exploration

The MNIST dataset is loaded and explored to understand its structure, image dimensions, and class distribution.

### 2. Data Preprocessing

- Reshape the image data when necessary.
- Normalize pixel values from the range [0, 255] to [0, 1].
- Prepare the labels and input data for model training.

### 3. Model Development

An Artificial Neural Network (ANN) is implemented using TensorFlow/Keras.

The model learns patterns and features from handwritten digit images to predict the corresponding digit.

### 4. Model Training

The model is trained using the training dataset, allowing it to adjust its weights and improve its classification performance over multiple epochs.

### 5. Model Evaluation

The trained model is evaluated using unseen testing data.

Performance is analyzed using:
- Accuracy.
- Loss.
- Confusion matrix.
- Prediction results.

### 6. Graphical User Interface

The trained model is integrated into a Tkinter application.

The interface allows users to interact with the model by drawing handwritten digits and receiving predictions.

## Project Structure

```text
MNIST/
│
├── notebooks/
│   └── mnist_training.ipynb
│
├── model/
│   └── mnist_model.keras
│
├── app/
│   └── main.py
│
├── requirements.txt
├── README.md
└── .gitignore
