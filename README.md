Breast Cancer Predictor Model Using Neural Networks

Description

This project is a machine learning model that predicts the likelihood of breast cancer based on patient data using a Neural Network (NN). The model is built using popular libraries like TensorFlow and Keras and provides predictions based on various features, including tumor characteristics such as radius, texture, perimeter, area, smoothness, and more.

Dataset

The model is trained on the Wisconsin Breast Cancer Dataset (WBCD), which contains 569 samples with 30 features per sample. Each sample represents a tumor and is labeled as either benign (0) or malignant (1).

Features

Mean Radius

Mean Texture

Mean Perimeter

Mean Area

Mean Smoothness

And more...

Libraries and Dependencies

TensorFlow (for building and training the Neural Network)

Keras (for neural network layers)

Pandas (for data manipulation)

NumPy (for numerical operations)

Matplotlib (for visualizations)

Scikit-learn (for dataset handling and evaluation)

Installation

To get started with the Breast Cancer Predictor model, follow these steps:


Input test data in the required format to get the prediction (0 for benign, 1 for malignant).

Model Evaluation

The model's performance is evaluated using the following metrics:

Accuracy

Precision

Recall

F1 Score

Results

The neural network achieved an accuracy of 93.8% on the test dataset.

The model performs well in predicting benign and malignant tumors, with high precision and recall values.

Contributing

Feel free to fork this project, make improvements, or submit issues and pull requests. Contributions are always welcome!
