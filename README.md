# Wine Quality Prediction using Machine Learning

This project focuses on predicting the quality of red wine based on its chemical properties. By analyzing various chemical attributes, we employ machine learning algorithms to classify the wine into different quality levels.

## Project Overview

The objective of this project is to model wine quality using physicochemical tests. We explor how factors like alcohol content, sulphates, and acidity influence the overall quality rating of red wine.

## Dataset Description

The dataset used is `wine.csv`, which consists of several physicochemical variables as inputs and one output variable (quality):

- **Fixed Acidity**: Most acids involved with wine or fixed or nonvolatile.
- **Volatile Acidity**: The amount of acetic acid in wine.
- **Citric Acid**: Found in small quantities, citric acid can add 'freshness' and flavor to wines.
- **Residual Sugar**: The amount of sugar remaining after fermentation stops.
- **Chlorides**: The amount of salt in the wine.
- **Free Sulfur Dioxide**: The free form of SO2 exists in equilibrium between molecular SO2 (as dissolved gas) and bisulfite ion.
- **Total Sulfur Dioxide**: Amount of free and bound forms of S02.
- **Density**: The density of wine is close to that of water depending on the percent alcohol and sugar content.
- **pH**: Describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic).
- **Sulphates**: A wine additive which can contribute to sulfur dioxide gas (S02) levels.
- **Alcohol**: The percent alcohol content of the wine.
- **Quality**: Output variable (based on sensory data, score between 0 and 10).

## Methodology

The project follows a structured data science workflow:
1. **Importing Libraries**: Utilizing `numpy`, `pandas`, `matplotlib`, and `seaborn`.
2. **Data Analysis**: Exploring the dataset using descriptive statistics and visualizations (histograms, box plots).
3. **Data Preprocessing**: Handling missing values, feature scaling using `StandardScaler`, and splitting the data into training and testing sets.
4. **Machine Learning Modeling**:
   - **K-Nearest Neighbors (KNN)**: Making predictions based on the proximity of data points.
   - **Support Vector Machine (SVM)**: Classifying wine quality by finding the optimal hyperplane.
5. **Evaluation**: Assessing model performance using accuracy scores and confusion matrices.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Machine Learning)

---
*Created as part of a Data Science Portfolio project.*
