# 🐔 Chicken-Disease-Classification-Project

## 📈Project Overview
This project focuses on building a deep learning model to classify chicken diseases based on images. The goal is to assist farmers and veterinarians in quickly identifying diseases in poultry, thereby improving animal health and reducing economic losses. The project leverages **TensorFlow** and **Keras** for building and training a convolutional neural network (CNN) model, and it includes a **Streamlit** web application for user-friendly interaction.

## 🔑Key Features
- **Deep Learning Model**: A CNN-based model trained to classify chicken diseases from images.
- **Data Pipeline**: Incorporates Data Version Control (DVC) for efficient data management and versioning.
- **Web Application**: A Streamlit app for users to upload images and get predictions.
- **Data Augmentation**: Techniques like rotation, flipping, and zooming to enhance the dataset.
- **Model Evaluation**: Metrics such as accuracy, precision, recall, and F1-score to assess model performance.
- **Continuous Integration/Continuous Deployment (CI/CD)**: Implements automated workflows using GitHub Actions for seamless deployment.
- **User-Friendly Interface**: Simple and intuitive interface for non-technical users.

## 🗂️Dataset
The dataset consists of images of chickens categorized into different disease classes. The classes include:
- Healthy
- Newcastle Disease
- Salmonellosis
- Coccidiosis
- Infectious Bronchitis

The dataset is split into training, validation, and test sets to ensure robust model evaluation.

## 🏗️Project Structure

Chicken-Disease-Classification-Project/
├── app/ # Streamlit application files
│ ├── app.py # Main Streamlit script
│ └── assets/ # Static files (e.g., CSS, images)
├── notebooks/ # Jupyter notebooks for EDA and model development
│ ├── 01_eda.ipynb # Exploratory Data Analysis
│ ├── 02_model_training.ipynb # Model training and evaluation
│ └── 03_model_testing.ipynb # Model testing and predictions
├── models/ # Saved models
│ └── chicken_disease_model.h5 # Trained CNN model
├── src/ # Source code
│ ├── data_preprocessing.py # Scripts for data loading and preprocessing
│ ├── model_training.py # Scripts for model training
│ └── utils.py # Utility functions
├── data/ # Dataset
│ ├── train/ # Training images
│ ├── val/ # Validation images
│ └── test/ # Test images
├── requirements.txt # Python dependencies
├── environment.yml # Conda environment (optional)
├── README.md # Project overview
└── .gitignore # Files to ignore in Git


## 📊Results
The trained CNN model achieved the following performance metrics on the test dataset:

- **Accuracy**: 92%
- **Precision**: 91%
- **Recall**: 90%
- **F1-Score**: 91%

## 🪄Web Application Demo
![Alt text](https://github.com/juna-99/Chicken-Disease-Classification-Project/blob/ba8e596595c69a20d4230e32a9a92f0cb0d020ad/blob/Screenshot%202025-02-17%20121826.png)
## 🚀Future Work
- **Expand Dataset**: Include more images and additional disease classes.
- **Improve Model**: Experiment with advanced architectures like ResNet or EfficientNet.
- **Deploy to Cloud**: Host the Streamlit app on a cloud platform for wider accessibility.
- **Mobile App**: Develop a mobile version of the application for on-the-go use.
