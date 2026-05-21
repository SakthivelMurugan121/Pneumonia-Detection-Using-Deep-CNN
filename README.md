# Pneumonia Detection Using Deep CNN

## Project Overview

This project presents a Deep Convolutional Neural Network (CNN) based approach for detecting Pneumonia from Chest X-ray images. The system uses multiple convolutional blocks with Batch Normalization, Max Pooling, and Dropout techniques to improve classification performance and reduce overfitting.

The model is trained and evaluated on Chest X-ray image datasets using TensorFlow and Keras. Performance evaluation includes Accuracy, Precision, Recall, F1-Score, AUC, ROC Curve analysis, and comparison with existing deep learning models.

---

## Features

* Deep CNN architecture for Pneumonia detection
* Batch Normalization for stable training
* Dropout regularization to reduce overfitting
* ROC Curve and AUC evaluation
* Performance comparison with existing CNN models
* Visualization of training accuracy and evaluation metrics
* Sample image prediction testing

---

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset

Chest X-ray image dataset containing:

* NORMAL images
* PNEUMONIA images

### Dataset Link

[https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

---

## Proposed CNN Architecture

The proposed model contains:

* Multiple Conv2D layers
* Batch Normalization
* ReLU Activation
* MaxPooling Layers
* Dropout Layer
* Fully Connected Dense Layers
* Softmax Output Layer

---

## Performance Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## Model Training

Training includes:

* Image preprocessing
* Data normalization
* Train / Validation / Test split
* Class balancing using class weights
* Early Stopping
* ReduceLROnPlateau scheduler

---

## Results

The proposed CNN model achieved strong performance for Pneumonia classification and demonstrated improvement using Dropout regularization techniques.


## Research Paper Reference

### Journal Paper

"Deep Learning Based Pneumonia Detection Using Chest X-Ray Images"

### Reference Link
(https://doi.org/10.1016/j.bbe.2022.08.001]

(Replace with your exact journal paper link if available)

---

## Future Improvements
* Transfer Learning using EfficientNet / DenseNet
* Attention Mechanism integration
* Explainable AI using Grad-CAM or SHAP
* Real-time clinical deployment

---

## Author
Sakthivel M

GitHub:
[https://github.com/SakthivelMurugan121](https://github.com/SakthivelMurugan121)
