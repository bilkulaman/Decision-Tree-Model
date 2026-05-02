📘 Liver Disease Prediction – Decision Tree Classifier

This project focuses on predicting whether a person is likely to have liver disease based on their medical test results. The dataset contains patient information such as enzyme levels, protein counts, and age. Using these features, a Decision Tree Classifier is trained to classify each person into:

1 = Liver Patient
2 = Not a Liver Patient

🔍 What This Project Does

✔ Loads and analyzes the dataset

✔ Handles missing values

✔ Converts categorical data (like Gender) into numbers

✔ Visualizes important patterns in the dataset

✔ Trains a machine-learning model using Decision Trees

✔ Evaluates model performance using:
1.Accuracy Score
2.Confusion Matrix
3.Classification Report

🌳 Why Decision Tree?

Decision Trees are easy to understand and explain.
They split data using simple “if-else” conditions, making them ideal for:
1.medical datasets
2.projects that require interpretability
3.beginners learning classification

📉 Model Performance
After tuning the Decision Tree (max depth, split criteria, leaf size), the model reaches:
1.~70% accuracy
2.Good generalization without overfitting
3.A simple, explainable structure

Outlier removal was tested, but it reduced accuracy, so the final model uses cleaned data without removing medical outliers, since extreme values may carry real diagnostic meaning.

📊 Key Visualizations

The project includes:
1.Class distribution of liver vs. non-liver patients
2.Boxplots of medical features
3.Confusion Matrix of final predictions

These help understand how the model behaves and how the data is structured.

⚙️ Technologies Used
Python
Pandas, NumPy
Seaborn, Matplotlib
Scikit-learn (DecisionTreeClassifier)

🧪 Goal of the Project

The goal is to practice data preprocessing, visualization, and model building while working with a real-world medical dataset — and to build a simple, interpretable model for liver disease prediction.
