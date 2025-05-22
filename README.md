# Simpson Character Name Prediction

This project is a deep learning-based image classification system designed to identify characters from *The Simpsons* TV show. It utilizes a Convolutional Neural Network (CNN) model trained on a labeled dataset of Simpsons character images.

## Project Overview

The model is trained using the Keras deep learning library and performs multi-class classification over a set of known Simpsons characters. The dataset includes a training set and a Kaggle-provided test set of unseen character images.

The notebook includes:

- Data preprocessing and image augmentation
- Model architecture using CNN layers
- Model training with validation metrics
- Evaluation and sample predictions on test images

## Model Summary

- **Trainable Parameters:** 17,591,274 (67.11 MB)  
- **Non-trainable Parameters:** 0  
- **Accuracy:** ~18% (subject to data quality and class imbalance)  
- **Loss:** Categorical Crossentropy

## Dataset

- **Source:** Kaggle Simpsons Character Dataset  
- **Number of classes:** Depends on labeled training set  
- **Test set:** Provided separately with unlabeled images for inference

## Key Dependencies

- Python 3.12  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- CAER (for image preprocessing)

Install dependencies via:

```bash
pip install tensorflow opencv-python-headless numpy matplotlib caer
