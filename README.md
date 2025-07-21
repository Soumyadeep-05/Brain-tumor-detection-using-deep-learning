# Brain Tumor Detection using Deep Learning (VAGG Model)

## Overview

This project presents a deep learning-based solution for automatic brain tumor detection and classification from MRI images using a custom VAGG Convolutional Neural Network (CNN) architecture. The tool aims to assist healthcare professionals in early tumor diagnosis, reduce manual errors, and accelerate workflow efficiency. With high classification accuracy, visual explanations, and flexible deployment, the system is designed to support real-time clinical applications and research.

## Features

- *VAGG CNN Architecture*
  - Custom-built VAGG model enables robust, accurate brain tumor classification from MRI scans.
- *Data Preprocessing & Augmentation*
  - Automated image preprocessing and data augmentation for improved model generalization and handling of diverse MRI datasets.
- *Comprehensive Evaluation*
  - Model performance measured using accuracy score, confusion matrix, and Grad-CAM for visual interpretation of predictions.
- *Deployment Ready*
  - Easily integrable into web or mobile applications for real-time tumor detection and reporting.
- *Extendable*
  - Framework supports multi-class classification (e.g., glioma, meningioma, pituitary tumors) and can be updated for further tumor subtypes.

## Tech Stack

- *Programming Language:* Python
- *Libraries & Frameworks:*
  - TensorFlow / Keras (deep learning and model training)
  - NumPy (numerical computations)
  - OpenCV (image processing)
  - Matplotlib (data and image visualization)

## How It Works

1. *Data Loading & Preprocessing*
   - MRI images are filtered, standardized, and augmented for effective model training.
2. *Model Training*
   - The VAGG CNN model learns features from preprocessed MRI images to classify tumor presence and type.
3. *Evaluation & Visualization*
   - Accuracy and confusion matrix provide statistical evaluation.
   - Grad-CAM generates heatmaps to visually explain model focus areas in MRI scans.
4. *Deployment*
   - Can be packaged as a Flask/Django web app or TensorFlow Lite mobile app for clinical usage.

## Results

- Model achieves high accuracy on validation and test data.
- Grad-CAM results confirm the model highlights relevant tumor regions in MRI images, supporting clinical trust.

## Future Improvements

- Integration with real-time MRI devices via APIs.
- Enhanced multi-class and subtype tumor classification.
- Deployment as cloud service or mobile application.
- EMR (Electronic Medical Record) integration for seamless healthcare workflows.

## Contributors

- Soumyadeep Roy
- Aryan Walia
- Lav Singh
