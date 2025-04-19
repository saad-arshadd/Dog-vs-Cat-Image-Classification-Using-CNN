# Dog vs Cat Image Classification Using CNN

## Project Overview

This project uses a **Convolutional Neural Network (CNN)** to classify images of dogs and cats. The dataset contains labeled images of dogs and cats, and the goal is to build a deep learning model that can predict whether a given image is of a dog or a cat. The model is built using TensorFlow and Keras, and the training process involves using data augmentation, normalization, and batch processing for efficient model training.

---

## Features

- **Data Preprocessing**: The dataset is divided into training and validation sets, and images are resized and normalized for better model performance.
- **CNN Architecture**: A Convolutional Neural Network is used with three convolutional layers, batch normalization, max-pooling, and fully connected layers.
- **Binary Classification**: The model classifies images into two categories: **0** (Cat) and **1** (Dog).
- **Model Training**: The model is trained on the dataset for 10 epochs, and training accuracy is plotted against validation accuracy.
- **Prediction**: The trained model can be used to predict whether an image contains a dog or a cat.

---

## Technologies Used

- **Python**: Programming language used to implement the project.
- **TensorFlow/Keras**: Deep learning framework for building and training the CNN model.
- **NumPy**: For numerical operations.
- **OpenCV**: For reading images.
- **Matplotlib**: For plotting training and validation accuracy graphs.

---

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/dog-vs-cat-cnn.git
cd dog-vs-cat-cnn
