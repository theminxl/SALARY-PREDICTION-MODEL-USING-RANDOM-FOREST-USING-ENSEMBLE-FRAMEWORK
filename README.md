💰 Salary Prediction using Ensemble Learning
📌 Project Overview

This project predicts whether an individual earns more than $50K per year using demographic and employment-related features from the Adult Census Income Dataset.

The model uses Ensemble Learning techniques to improve classification performance and stability. Multiple machine learning models are combined using a Voting Classifier to generate final predictions.

📊 Dataset

Dataset Used: Adult Census Income Dataset (UCI / Kaggle)

The dataset includes features such as:

Age

Workclass

Education

Education Number

Marital Status

Occupation

Relationship

Race

Sex

Capital Gain

Capital Loss

Hours per Week

Native Country

Target Variable:

<=50K

>50K

⚙️ Project Workflow
1️⃣ Data Preprocessing

Removed duplicate records

Checked missing values

Label encoded categorical features

Train-Test split

2️⃣ Exploratory Data Analysis (EDA)

Visualizations include:

Income distribution count plot

Age distribution by income

Working hours vs income (boxplot)

Pairplot for feature relationships

3️⃣ Machine Learning Models Used

Decision Tree Classifier

Random Forest Classifier

AdaBoost Classifier

Voting Classifier (Soft Voting – Final Model)

4️⃣ Model Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Classification Report

📈 Model Performance

The ensemble model achieved approximately:

Accuracy: ~85%+

Balanced precision and recall

Improved stability over individual models

🌳 Feature Importance

Random Forest feature importance visualization highlights the most influential factors affecting income prediction, such as:

Education Number

Hours per Week

Age

Capital Gain

🔍 Model Visualization

Confusion Matrix heatmap

Model accuracy comparison graph

Pairplot for feature interaction

Decision Tree visualization using Graphviz

🔮 Interactive Prediction

The project allows manual input of encoded feature values to:

Predict income category

Display prediction probability

Example Output:

Predicted Income: >50K
Probability of <=50K: 0.21
Probability of >50K: 0.79
🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Graphviz

🚀 How to Run

Clone this repository

Install required libraries

Run the notebook or Python script

Enter encoded values for prediction

🎯 Conclusion

Ensemble learning significantly improves prediction performance by combining multiple weak and strong learners. The Voting Classifier produces more stable and accurate results compared to individual classifiers.

This project demonstrates:

Data preprocessing

Feature engineering

Model comparison

Ensemble learning

Model visualization

Interactive prediction system
