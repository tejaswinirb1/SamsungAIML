# Brain Tumor Detection  
This project uses a Convolutional Neural Network (CNN) to classify brain tumors from MRI images into four categories: pituitary, no tumor, meningioma, and glioma. The model is trained on preprocessed MRI data to assist in accurate tumor detection and diagnosis.
## Acknowledgement
This project was developed as final project for completing the Samsung Innovation Campus.I extend my gratitude to SIC for giving the opportunity and resources to complete this project.
## Description
This project involves creating a deep learning model for brain tumor classification using MRI images. The model uses a Convolutional Neural Network (CNN) to classify brain tumors into four categories: **pituitary tumor**, **no tumor**, **meningioma**, and **glioma**. Images are preprocessed by converting them to grayscale, resizing, and normalizing before being fed into the CNN. The model consists of multiple convolutional layers, followed by max-pooling and fully connected layers, and is trained on labeled MRI images. The goal is to accurately predict the tumor type from new MRI images, aiding in medical diagnostics.
## Technologies Used
* Python
* Google colab
* Streamlit
## Features
* Utilizes a CNN architecture for efficient image recognition and classification.
* Preprocesses MRI scans by resizing, normalizing, and converting them to grayscale.
* Classifies brain tumors into four categories: pituitary, no tumor, meningioma, and glioma.
* Trains the model on labeled MRI data and evaluates its performance on a test dataset.
* Incorporates dropout to reduce overfitting during training.
* Provides a user interface to upload MRI images for classification through Streamlit.
