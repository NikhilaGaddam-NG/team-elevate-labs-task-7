🧠 SVM Classification on Breast Cancer Dataset
This project demonstrates how to use Support Vector Machines (SVMs) for both linear and non-linear classification tasks using the Breast Cancer Wisconsin dataset.

📌 Objective
Perform binary classification using SVM.
Apply both Linear and RBF (Radial Basis Function) kernels.
Visualize decision boundaries.
Tune SVM hyperparameters using GridSearchCV.
Evaluate model performance using cross-validation.
🛠️ Tools & Libraries
Python
NumPy
Pandas
Matplotlib
Scikit-learn
📂 Dataset
File: breast-cancer.csv
Columns include tumor features (mean radius, texture, smoothness, etc.).
Target column: diagnosis (M for Malignant, B for Benign).
🚀 Steps Performed
Load and preprocess the dataset

Convert diagnosis to binary labels (M → 1, B → 0).
Drop non-informative columns like id, Unnamed: 32.
Feature scaling and dimensionality reduction

Features are scaled using StandardScaler.
PCA (Principal Component Analysis) is used to reduce features to 2D for visualization.
Train SVM models

Trained two models using:
Linear kernel
RBF kernel
Visualize decision boundaries

Decision regions are plotted in 2D using the PCA-transformed data.
Hyperparameter tuning

Used GridSearchCV to find optimal values for C and gamma.
Model evaluation

Accuracy and classification report on test data.
Cross-validation score on the full dataset.
📊 Results
Achieved high accuracy using both linear and RBF kernels.
RBF generally performed slightly better after tuning.
Visual decision boundaries show clear class separation.
