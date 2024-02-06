# Breast Cancer Classification

This is a machine learning project that aims to classify breast cancer tumors as malignant or benign based on various features extracted from digitized images of fine needle aspirate (FNA) of breast masses.

## Data

The data used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set from the UCI Machine Learning Repository. It contains 569 instances of tumors with 30 numeric features and 2 classes (M = malignant, B = benign). The features are computed from a digitized image of a FNA of a breast mass. They describe characteristics of the cell nuclei present in the image.

## Models

Two different machine learning models are used for this project: logistic regression and support vector machine. Both models are implemented using scikit-learn, a popular Python library for machine learning. The models are trained and evaluated on the data using accuracy, confusion matrix, and classification report as the metrics.

## Files

The project consists of two Jupyter notebooks, each containing the code for one model. The files are:

- AbednegoNdegwa_model_v1.ipynb: This file contains the code for the logistic regression model. It follows the steps of data exploration, preprocessing, training, and evaluation.
- AbednegoNdegwa_model_v2.ipynb: This file contains the code for the support vector machine model. It follows the same steps as the logistic regression model, but with a different model and parameters.

## References

- [Breast Cancer Wisconsin (Diagnostic) Data Set]: This is the original source of the data that is used for this project. It contains the description of the features, the classes, and the references for the data collection and analysis.
- [scikit-learn]: This is the Python library that is used for implementing the machine learning models and the evaluation metrics. It provides a user-friendly and consistent interface for various machine learning algorithms and tools.
