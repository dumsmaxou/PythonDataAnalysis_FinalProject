# PythonDataAnalysis_FinalProject

This project is based on the QSAR biodegradation data set (https://archive.ics.uci.edu/ml/datasets/QSAR+biodegradation).

The goal was to be able to determine if a chemical element is biodegradable or not. And find the most accuracy model which can determine this.

I tried 4 differents models (Logistic Regression, k-NN, PLSRegression and SVM). The best ones are Logistic Regression and sometimes SVM (depends of the distribution of Train/Test sets).
I obtained an accuracy of approximatly 0.90, and created an API to determine if future chemical element will be biodegradable or not.
