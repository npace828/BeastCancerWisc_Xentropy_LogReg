# Breast Cancer Detection Model

## Overview
This repository contains a Python implementation of a logistic regression model for breast cancer detection using the Breast Cancer Wisconsin (Diagnostic) dataset. The model predicts whether a tumor is malignant or benign based on various features extracted from cell nuclei images.

## Dataset
The Breast Cancer Wisconsin (Diagnostic) dataset contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. The features describe characteristics of the cell nuclei present in the images. The dataset includes the diagnosis (malignant or benign) as the target variable.

## Implementation
- The code uses logistic regression as the classification algorithm to build the breast cancer detection model.
- Preprocessing steps include power transformation and scaling of the features using a pipeline with the Yeo-Johnson method and MinMaxScaler.
- The model's performance is evaluated using accuracy, confusion matrix, and classification report metrics.
- The loss function (Binary Cross Entropy) is visualized to monitor the model's training progress.

## Usage
1. Ensure you have Python installed on your machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the `breast_cancer_detection.py` script to train and evaluate the model.
4. View the visualizations and metrics to assess the model's performance.

## Files
- `breast_cancer_detection.py`: Main Python script containing the implementation of the breast cancer detection model.
- `README.md`: This file providing an overview of the project.
- `requirements.txt`: Text file listing the required Python packages and their versions.

## References
- [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/index.html)

## Author
[Your Name]

