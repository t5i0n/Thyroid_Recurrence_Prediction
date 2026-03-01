# Thyroid Recurrence Prediction

This project leverages machine learning techniques to forecast the likelihood of thyroid condition recurrence in patients using clinical data. It evaluates the performance of two models—Decision Tree and K-Nearest Neighbors (KNN)—to identify the most reliable approach for this medical prediction task.  

## Project Overview 

The goal is to predict whether a patient will experience recurrence (`Recurred: Yes/No`) based on their clinical and demographic information.  

**Models Used:**  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  

**Top Performer:**  
- **Decision Tree** – Accuracy: ~97.4%, Recall: 95%  

**Techniques Applied:**  
- Mode imputation for missing data  
- Label encoding for categorical variables  
- One-hot encoding for nominal features  
- Feature scaling using StandardScaler  

## Dataset

The analysis uses `filtered_thyroid_data.csv`, containing patient records with these categories of features:  

- **Demographics:** Age, Gender  
- **Medical History:** Hx Radiotherapy, Adenopathy  
- **Pathology:** Pathology type, Focality, Risk  
- **Staging:** T, N, M, Stage  
- **Outcome:** Response, Recurred (target variable)  

