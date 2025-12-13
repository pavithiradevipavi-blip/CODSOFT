# CODSOFT
# Titanic Survival Prediction

## Overview
This project predicts whether a passenger survived the Titanic disaster using **machine learning**.  
It uses historical passenger data including age, gender, class, fare, and other features to make predictions.

## Dataset
The dataset is from [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset).  
It contains information about individual passengers such as:
- Passenger Class (Pclass)  
- Name, Sex, Age  
- SibSp (siblings/spouses aboard)  
- Parch (parents/children aboard)  
- Ticket, Fare, Cabin, Embarked  
- Survived (Target variable)

## Features Used
- Pclass  
- Sex  
- Age  
- SibSp  
- Parch  
- Fare  
- Embarked  

## Preprocessing
- Dropped unnecessary columns: `Cabin`, `Name`, `Ticket`  
- Filled missing `Age` values with median  
- Filled missing `Embarked` values with mode  
- Converted categorical values (`Sex` and `Embarked`) to numeric

## Model
- **Algorithm:** Logistic Regression  
- **Train/Test Split:** 80% / 20%  
- **Purpose:** Predict survival (0 = Did not survive, 1 = Survived)

## Results
The model predicts survival with good accuracy on the test set.  
- Example output: `Model Accuracy: 79.78%`

## How to Run
1. Open the notebook `Titanic dataset` in Google Colab  
2. Upload `Titanic-Dataset.csv.csv` dataset  
3. Run the cells step by step  

## Author
**A. Pavithira Devi**  
CodSoft Internship – December Batch B70