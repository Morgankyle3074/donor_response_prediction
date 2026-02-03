# Donor Response Prediction

This project builds and compares multiple classification models to predict whether a prospective donor will respond to a fundraising mailing using demographic and historical giving data.

## Objective
Determine how well donor response can be predicted and identify which modeling approach performs best.

## Models Used
- Logistic Regression  
- Linear Discriminant Analysis (LDA)  
- Quadratic Discriminant Analysis (QDA)  
- K-Nearest Neighbors (KNN)  

## Workflow
- Data cleaning and preprocessing  
- Handling missing values  
- Encoding categorical variables  
- Train/test split  
- Model training  
- Evaluation using confusion matrices, accuracy, sensitivity, specificity, ROC curves, and AUC  

## Results Summary
Logistic Regression and LDA provided the strongest overall performance with a good balance between predictive accuracy and interpretability. Logistic Regression is recommended due to its strong performance and ease of explanation.

## Tools
R, tidyverse, MASS, caret, class, pROC

## Files
- donor_project.Rmd – Reproducible analysis  
- donor_project.docx/pdf – Final report  
- donor_models.R – Script version of models  

## Data
Dataset provided as part of university coursework and is not included due to licensing restrictions.
