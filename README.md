# Image Classification with CNN and Data Augmentation

## Overview
This project builds a **Convolutional Neural Network (CNN)** to classify images from the CIFAR-10 dataset into 10 categories. The analysis compares model performance with and without **data augmentation**, demonstrating how augmentation techniques improve generalization and reduce overfitting.

Completed as coursework for **DATA 440 (Advanced Machine Learning)** at the University of Maryland Global Campus.

## Business Problem
Image classification is a foundational task in computer vision with applications across industries — from quality control in manufacturing to document processing in financial services. Understanding how CNNs learn visual features and how data augmentation improves model robustness is essential for any data scientist working with visual data.

## Dataset
- **Source:** [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) (built into Keras)
- **Size:** 60,000 color images (50,000 training, 10,000 test)
- **Image size:** 32x32 pixels, 3 color channels (RGB)
- **Classes:** 10 categories — airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

## Methods
- Built a CNN architecture using TensorFlow/Keras with Conv2D, MaxPooling, Dropout, and Dense layers
- Trained baseline model without augmentation
- Applied **data augmentation** using Keras ImageDataGenerator (rotation, horizontal flip, width/height shift, zoom)
- Compared training curves, accuracy, and overfitting between augmented and non-augmented models
- Visualized sample images and augmentation effects

## Key Findings
- The baseline model without augmentation showed signs of **overfitting** — high training accuracy but lower test accuracy
- **Data augmentation reduced overfitting** by exposing the model to varied versions of training images
- The augmented model achieved better **generalization** to unseen test data
- Augmentation techniques like horizontal flipping and rotation were most effective for this dataset

## Tools & Libraries
- Python (TensorFlow/Keras, NumPy, matplotlib)
- Jupyter Notebook

## Files
- `CNN_Image_Classification_Data_Augmentation.ipynb` — Full CNN analysis with and without data augmentation

## Author
**Julio Patiño**
- [LinkedIn](https://www.linkedin.com/in/juliopatino88/)
- [GitHub](https://github.com/juliopatino88)
