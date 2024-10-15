# Face Mask Detection

**Face Mask Detection** is a machine learning project that employs computer vision techniques to identify whether individuals are wearing face masks in images. This project aims to promote safety and compliance with health regulations, especially during the ongoing pandemic, by providing a reliable tool for mask detection in real-time.

## Introduction

Face mask detection plays a crucial role in ensuring public health and safety by monitoring compliance with mask-wearing guidelines. This project implements a deep learning model to detect face masks in images or video feeds. The model is trained on a dataset of labeled images, allowing it to learn the visual characteristics of individuals wearing masks versus those without.

The project utilizes Convolutional Neural Networks (CNNs) for image classification, making it effective for detecting faces in various environments and lighting conditions. This solution has significant applications in public spaces, businesses, and transportation systems to enhance safety measures.

## Installation

- Clone the repository to your local machine.
- Navigate to the project directory.
- Install the necessary dependencies.
- Prepare the dataset of face images organized into categories (with masks and without masks).

## Usage

- Preprocess the images to ensure compatibility with the model input size.
- Train the face mask detection model on the prepared dataset using the `train_mask_detector.py` file.
- Use the `mask_detector.py` to perform mask detection on images.
- Employ the `face_detector.py` for detecting faces in images.
- Utilize the `face_mask_video.py` file to analyze video streams for real-time face mask compliance.
- Use the `detect_mask_image.py` file to analyze single images for face mask detection.

## Features

- **Real-Time Detection**: Capable of detecting face masks in images and video feeds in real-time.
- **CNN-Based Image Classification**: Utilizes Convolutional Neural Networks to accurately classify individuals with or without face masks.
- **Multi-Environment Adaptability**: Designed to work effectively in various environments and lighting conditions.
- **Custom Dataset Training**: Allows training on custom datasets for tailored detection solutions.

## Applications

- **Public Health Compliance**: Monitors compliance with mask-wearing regulations in public spaces.
- **Security Systems**: Integrates with security systems to enhance safety measures in businesses and public transportation.
- **Research**: Supports research in public health and safety by providing a tool for analyzing mask compliance.

## System Requirements

- Python 3.x
- Deep learning frameworks such as TensorFlow or PyTorch
- A dataset of face images organized into class-specific directories (with masks and without masks)
- Jupyter Notebook (optional for development and testing)

## Conclusion

The **Face Mask Detection** project provides an efficient solution for automating the detection of face masks in images and video feeds. By leveraging CNNs, the model can learn to identify whether individuals are wearing masks, promoting safety and compliance with health regulations in various environments.
