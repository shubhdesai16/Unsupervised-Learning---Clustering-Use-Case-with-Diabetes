# Unsupervised-Learning Clustering Use Case with Diabetes
<b>Description</b>

This project explores the use of unsupervised learning techniques, specifically clustering, to predict diabetes in patients based on various medical attributes. The dataset, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases and downloaded from Kaggle, includes medical predictors such as age, BMI, blood pressure, and glucose levels.

<b> Key Components </b>

Problem Statement: Predict diabetes in patients using medical attributes.

Importance: Early detection of diabetes can lead to better management and prevention strategies, improving patient outcomes and reducing healthcare costs.

Dataset: Contains 768 rows and 9 columns, with attributes such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age.

<b> Methodology </b>

Data Preparation: Handling missing values and splitting data into training (80%) and testing (20%) sets.

Model Selection: K-means Clustering and Affinity Propagation algorithms were used.

Model Evaluation: Evaluated using Davies-Bouldin Score, Silhouette Score, Variance Ratio Criterion, and Fowlkes-Mallows Scores.

<b>Results & Conclusions</b>

Results: K-means Clustering with 2 and 3 clusters performed well, with Affinity Propagation showing higher cluster values.

Conclusions: Future improvements include adding more features and applying advanced techniques like ensemble learning. The solution has potential real-life applications in healthcare systems for early diabetes diagnosis, enhancing patient care, and reducing long-term healthcare costs.

<b> Key Learnings </b>

The importance of data preprocessing and feature engineering.

The value of model evaluation metrics in selecting the best model for deployment.

Insights into the application of machine learning in healthcare.
