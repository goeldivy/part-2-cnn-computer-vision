
# CNN-Based Computer Vision Analysis

## Objective
This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras.

The objective is to classify images into multiple categories and demonstrate practical understanding of deep learning and computer vision concepts.

---

# Task 1: Problem Identification

The dataset represents an Image Classification problem because each image belongs to one predefined category.

The CNN model learns image features and predicts the correct image class.

Dataset classes:
- dent
- normal
- scratch
- stain

---

# Task 2: Dataset Exploration

The dataset was analyzed by:
- identifying the number of classes
- counting images per class
- visualizing sample images
- checking image dimensions
- analyzing dataset balance

The dataset appears balanced because all classes contain approximately equal numbers of images.

---

# Task 3: Image Preprocessing

The preprocessing steps included:
- resizing images to 128×128
- normalizing pixel values
- splitting data into training and validation sets
- applying image augmentation

Image augmentation techniques used:
- rotation
- zooming
- horizontal flipping

---

# Task 4: CNN Model Creation

The CNN architecture includes:
- Convolution layers
- ReLU activation functions
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

The model was compiled using:
- Adam optimizer
- categorical crossentropy loss
- accuracy metric

---

# Task 5: Model Training and Evaluation

The CNN model was successfully trained and evaluated.

Evaluation methods included:
- training accuracy
- validation accuracy
- loss analysis
- confusion matrix
- sample image prediction

The model achieved strong classification performance on the validation dataset.

---

# Task 6: CNN Concept Explanation

## What is Convolution?
Convolution is a mathematical operation used in CNNs to extract image features such as edges, textures, and shapes.

## Why is Pooling Used?
Pooling reduces image dimensions and computational complexity while preserving important features.

## Why is ReLU Commonly Used?
ReLU introduces non-linearity into the model and helps CNNs learn complex image patterns efficiently.

## Why are CNNs Better than Feed-Forward Networks for Images?
CNNs automatically learn spatial image features and preserve visual relationships, making them more efficient for image data.

---

# Task 7: Business Use Case Mapping

## Manufacturing Industry Use Case

This CNN-based computer vision solution can be used in manufacturing industries for automatic defect detection.

The model can identify defects such as:
- dents
- scratches
- stains

Benefits include:
- improved quality inspection
- reduced manual effort
- faster defect detection
- higher production efficiency

---

# Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Project Files

- notebook.ipynb
- cnn_model.h5
- README.md
- requirements.txt
- results/
- sample_predictions/

---

# Conclusion

The CNN-based computer vision project successfully demonstrated image classification using deep learning techniques.

The project covered:
- image preprocessing
- CNN model building
- training and evaluation
- confusion matrix analysis
- sample prediction generation

This project demonstrates practical implementation of computer vision concepts using Convolutional Neural Networks.



## Note

The trained CNN model file (.h5) was excluded from the GitHub repository due to file upload limitations.


## Dataset Note

The dataset used for this project was provided separately through the assignment shared drive and was excluded from the GitHub repository due to file size considerations.

## Model File Note

The trained CNN model file was excluded from GitHub upload due to repository upload limitations.