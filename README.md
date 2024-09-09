# Logistic-Regression-For-Malaria-Cell-Images-Dataset
Model of logistic regression 

Image Classification with HOG Features and SGDClassifier
In this project, I developed an image classification model using Histogram of Oriented Gradients (HOG) features and a Stochastic Gradient Descent (SGD) Classifier. The model was trained and evaluated on a dataset of cell images. Additionally, I created a user-friendly graphical interface (GUI) for easy predictions.

Key Features
Feature Extraction: Utilized HOG features for robust image representation.
Classification: Applied SGDClassifier with logistic loss for classification.
Preprocessing: Standardized features for improved performance.
Evaluation: Comprehensive evaluation using accuracy, ROC curve, confusion matrix, and loss curves.
GUI: Developed a graphical user interface for easy image uploads and predictions.
Results
Accuracy: 86%
AUC (Area Under the Curve): 0.93
Visualizations
ROC Curve: Shows the performance of the classifier across different thresholds.
Confusion Matrix: Provides a detailed breakdown of classification performance.
Loss Curve: Illustrates the training and testing loss over iterations.
Code Details
The code processes images from a dataset, extracts HOG features, trains an SGDClassifier, and evaluates the model using various metrics. The implementation includes:

Data Loading and Preprocessing: Resizing images, feature extraction, and standardization.
Model Training: Using SGDClassifier with logistic loss and regularization.
Evaluation: Metrics like accuracy, classification report, ROC curve, and confusion matrix.
GUI: Allows users to upload an image and receive predictions with a graphical interface.
For more details and to explore the code, please visit the repository.
