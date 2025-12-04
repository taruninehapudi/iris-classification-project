# iris-classification-project

Project Overview:

• Classification of Iris flower species using machine learning
• Includes exploratory data analysis, preprocessing, feature scaling, and model training
• Incorporates both beginner-friendly steps and a few advanced concepts such as Pipelines, GridSearchCV, PCA visualization, and permutation feature importance
• Provides insights into which flower measurements contribute most to species prediction

Objectives

• Understand patterns in Iris flower measurements
• Build and compare classification models (KNN, SVM, Decision Tree)
• Analyze feature importance and visualize class separation
• Tune hyperparameters using GridSearchCV for improved performance
• Save a reusable ML pipeline for future predictions

Tools Used

• Python
• Pandas
• NumPy
• Scikit-learn
• Matplotlib
• Jupyter Notebook

Files in This Repository

• Iris_Classification_Beginner_Advanced.ipynb — Main notebook
• iris.csv — Sample dataset
• iris_beginner_bundle.joblib — Saved model pipeline
• README.md — Project documentation

Dataset Source

• Dataset loaded from local storage (iris.csv)
• Sample dataset included for demonstration and reproducibility

Important Note (Path Adjustment Required)

• The notebook loads the dataset from a local path
• Users must update the file path on their system if needed
• Alternatively, place iris.csv in the same folder as the notebook

Key Insights

• Petal length and petal width are the strongest predictors of species
• PCA visualizations show clear separation of Iris-setosa and partial overlap between the other two species
• The tuned SVM model achieved the best performance among all tested models
• Feature importance analysis highlights petal-based features as primary contributors

Business / Scientific Interpretation

• Strong separation in petal features indicates they are reliable indicators for species classification
• Consistent performance across models demonstrates the dataset's suitability for ML tasks
• Insights can support teaching, botanical classification studies, and ML workflow demonstrations
• The saved pipeline enables easy deployment for prediction applications

How to Run

• Download this repository

• Ensure iris.csv is in the same folder as the notebook

• Install required libraries using:

      pip install -r requirements.txt

• Open the notebook in Jupyter

• Update dataset file path if necessary

• Run all cells sequentially
