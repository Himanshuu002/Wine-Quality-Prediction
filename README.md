

🍷 Wine Quality Prediction

This project focuses on predicting the quality of red wine using various machine learning algorithms based on physicochemical tests. The dataset is publicly available and widely used for classification tasks in ML.


📁 Dataset
Source: UCI Machine Learning Repository


File: winequality-red.csv


Attributes: Fixed acidity, Volatile acidity, Citric acid, Residual sugar, etc.


Target: Wine Quality (Score between 0–10)



🧠 Machine Learning Workflow
Data Collection
Load the dataset using pandas.

Data Preprocessing

Handle missing values

Normalize/standardize features

Encode categorical variables if present


Exploratory Data Analysis (EDA)

Histograms, Heatmaps, Pairplots

Correlation matrix


Model Building
Multiple algorithms tested, such as:

Logistic Regression,
Decision Tree,
Random Forest,
Support Vector Machine,
K-Nearest Neighbors..


Model Evaluation

Accuracy,
Confusion Matrix,
Classification Report,
ROC Curve (if applicable)..


🛠️ Requirements
Typical libraries used:

pandas,
numpy,
matplotlib,
seaborn,
scikit-learn..


🚀 How to Run
Clone the repo
git clone https://github.com/Himanshuu002/wine-quality-prediction.git


Navigate to the project folder
cd wine-quality-prediction


Launch the Jupyter Notebook
jupyter notebook Wine_quality_prediction_.ipynb


📊 Sample Visualizations
Correlation heatmap showing relation among features


Countplot of wine quality classes


Feature importance chart from Random Forest

📌 Conclusion
The project highlights the importance of feature selection, normalization, and model comparison in predictive analytics. Random Forest or SVM usually perform best for this dataset.
