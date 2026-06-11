# DermaNode AI

Early Skin Cancer Detection using Deep Learning and Explainable AI

## Overview

DermaNode AI is a computer vision system for early dermatological screening. The model uses transfer learning with EfficientNet-B3 to classify dermoscopic images into seven skin lesion categories from the HAM10000 dataset.

## Features

* 7-Class Skin Lesion Classification
* EfficientNet-B3 Transfer Learning
* Class Imbalance Handling
* Data Augmentation Pipeline
* Grad-CAM Explainability
* FastAPI-Ready Deployment Pipeline

## Dataset

HAM10000 Dataset

* 10,015 dermoscopic images
* 7 lesion categories
* Public medical imaging benchmark

## Model

Architecture:
EfficientNet-B3 + Global Average Pooling + Dropout + Softmax(7)

## Results

* Validation Accuracy: ~85%
* Multi-class Classification
* Explainable Predictions using Grad-CAM

## Technology Stack

Python • TensorFlow • EfficientNet • NumPy • Pandas • Scikit-Learn

## Future Work

* Clinical Validation
* Mobile Deployment
* FastAPI Inference Service
* Multi-modal Dermatology Assistant

## Disclaimer

This project is intended for educational and research purposes only and is not a substitute for professional medical diagnosis.

