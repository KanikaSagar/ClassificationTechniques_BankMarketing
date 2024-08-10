# Exploring Classification Techniques for Bank Marketing

## Project Overview

This project explores various machine learning classification techniques to predict whether a client will subscribe to a term deposit based on demographic and marketing features. By leveraging these models, banks can optimize their marketing strategies and improve customer engagement.

## Objective

The primary objective of this project is to develop a predictive model that accurately determines whether a client will make a deposit. The project utilizes a dataset containing attributes such as age, job, marital status, education, housing situation, and more. We aim to build a robust classification model to classify clients into two categories: likely to make a deposit and unlikely to make a deposit.

## Dataset

The dataset used for this project consists of:

- **Training Dataset**: 41,188 rows and 21 columns
- **Testing Dataset**: 4,119 rows and 21 columns

These datasets contain both numerical and categorical features relevant to the prediction task.

## Methodology

1. **Data Preprocessing**
   - Checked for missing and duplicate values.
   - Applied one-hot encoding for categorical features.
   - Used a standard scaler for feature scaling.

2. **Exploratory Data Analysis**
   - Visualized relationships between features and target variable using heatmaps and plots.

3. **Model Implementation**
   - Implemented several classification models, including:
     - Logistic Regression
     - Decision Tree
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Gaussian Naïve Bayes
     - Random Forest
     - AdaBoost Classifier

4. **Model Evaluation**
   - Used accuracy scores and ROC curves to evaluate model performance.
   - Random Forest Classifier achieved the highest accuracy and is recommended for practical applications.

## Conclusion

The Random Forest Classifier outperformed other models in terms of accuracy and ROC AUC score, making it a robust choice for predicting term deposit subscriptions. This approach can assist banks in targeting potential depositors more accurately and efficiently.

## Author

- **Kanika Sagar**: sagar.kanika1424@gmail.com

## Contribution

The entire project was contributed to by Kanika Sagar.

## Acknowledgements

This project was completed as part of the Advanced Professional Certification Program in Data Science & Machine Learning at IIT Guwahati under the guidance of Prof. Babji Srinivasan.

## Repository Contents

- **SourceCode_Capstone_Bank_Marketing.ipynb**: Jupyter Notebook containing the source code and implementation details.
- **CapStone_Classification_Techniques_For_Bank_Marketing.docx**: Detailed project report documenting the analysis and results.


