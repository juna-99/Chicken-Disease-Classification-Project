# 🐔 Chicken Disease Classification

## 📈Project Overview
This project focuses on building a deep learning model to classify chicken diseases based on images. The goal is to assist farmers and veterinarians in quickly identifying diseases in poultry, thereby improving animal health and reducing economic losses. This project implements a deep learning-based pipeline to detect and classify chicken diseases from images. It follows a full-stack MLOps approach, covering model training, deployment, CI/CD automation, and cloud hosting.

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

![Alt text](https://github.com/juna-99/Chicken-Disease-Classification-Project/blob/be486f8d8edc8f3319c50ce490846515ef1ac4cd/blob/Screenshot%202025-02-17%20122500.png)

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
