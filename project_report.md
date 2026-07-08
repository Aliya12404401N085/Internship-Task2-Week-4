Project Report
Week 4 - Task 2: Machine Learning Workflow
Project Title
Machine Learning Workflow Using the Iris Dataset
Problem Statement
The objective of this project is to build and compare machine learning models for predicting flower species using the Iris dataset. The project includes data preprocessing, exploratory data analysis, model training, evaluation, and performance comparison.
Dataset
Dataset Name: Iris Dataset
Source: Scikit-learn
Samples: 150
Features:
Sepal Length
Sepal Width
Petal Length
Petal Width
Target:
Setosa
Versicolor
Virginica
Data Preprocessing
The dataset was checked for missing values and duplicate records. Since the Iris dataset is clean, no missing values were found. Features were scaled before model training to improve performance.
Exploratory Data Analysis
Several visualizations were created to understand the dataset:
Feature Distribution
Correlation Heatmap
Pair Plot
Class Distribution
These visualizations helped identify relationships between variables and class separation.
Machine Learning Models
Two supervised learning models were implemented:
Logistic Regression
Random Forest Classifier
Model Evaluation
The models were evaluated using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Random Forest achieved the highest accuracy and performed better than Logistic Regression.
Results
Logistic Regression performed well with high classification accuracy.
Random Forest produced the best overall performance.
The dataset is easily separable because of clear feature differences between classes.
Business Insights
Machine learning models can classify flower species accurately with minimal preprocessing. Comparing multiple algorithms helps identify the best-performing model for prediction tasks. Similar workflows can be applied to healthcare, agriculture, finance, and business analytics.
Conclusion
This project demonstrated the complete machine learning workflow, including preprocessing, visualization, model training, evaluation, and comparison. Random Forest outperformed Logistic Regression and was selected as the better model for this dataset.
Libraries Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Joblib
