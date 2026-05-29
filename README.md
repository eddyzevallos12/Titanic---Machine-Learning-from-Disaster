# 🚢 Titanic - Machine Learning from Disaster
 
> **Kaggle Getting Started Competition** | My first Data Science project
 
This repository contains my solution to Kaggle's classic introductory challenge: predicting passenger survival on the Titanic using Machine Learning. I'm sharing it as part of my transition into a Data Science career, documenting what I learned along the way.
 
---
 
## 📌 Project Overview
 
The challenge consists of analyzing Titanic passenger data (age, gender, class, etc.) and building a model to predict who survived the shipwreck. More than the final score, the value lies in going through the full data science pipeline end-to-end.
 
**Goal:** Binary classification — survived (1) or did not survive (0)
 
---
 
## 🛠️ Tech Stack
 
| Tool | Purpose |
|---|---|
| Python | Main language |
| Pandas | Data manipulation & cleaning |
| Scikit-learn | Modeling (Random Forest Classifier) |
| Jupyter Notebook | Development environment |
 
---
 
## 📂 Repository Structure
 
```
Titanic---Machine-Learning-from-Disaster/
├── main.ipynb        ← Full pipeline: preprocessing + model + predictions
├── requirements.txt   ← Python dependencies for easy installation
├── gender_submission.csv  ← Kaggle's sample submission format
├── train.csv         ← Training dataset
├── test.csv          ← Test dataset
├── submission.csv        ← Final predictions submitted to Kaggle
└── README.md
```
 
---
 
## 🔍 What I Did
 
### 1. Data Cleaning & Preprocessing
- Identified and handled missing values in key columns (`Age`, `Cabin`, `Embarked`)
- Dropped columns with too many nulls or low predictive value
- Imputed missing numeric values using median/mode strategies
### 2. Feature Engineering & Transformation
- Encoded categorical variables (`Sex`, `Embarked`) into numeric format
- Transformed relevant features for model compatibility
- Selected the most meaningful features based on domain logic
### 3. Modeling with Random Forest
- Trained a Random Forest Classifier on the cleaned dataset
- Analyzed feature importances to understand what drove predictions
- Generated final predictions on the test set and submitted to Kaggle
---
 
## 💡 Key Takeaways
 
- Data cleaning is not optional — garbage in, garbage out
- Understanding **why** you drop or impute a column matters as much as knowing how
- The full pipeline (raw data → clean data → model → submission) teaches more than any tutorial
- Documenting your reasoning as you go makes the project reproducible and shareable
---
 
## 📊 Kaggle Result
 
Project completed and submitted as part of the learning process. The focus was on understanding the full workflow: cleaning → transforming → modeling → predicting.
 
---
 
## 🚀 How to Run
 
```bash
# Clone the repository
git clone https://github.com/eddyzevallos12/Titanic---Machine-Learning-from-Disaster.git
 
# Install dependencies
pip install -r requirements.txt
 
# Open the notebook
jupyter notebook main.ipynb
```
 
---
 
## 🔗 Original Competition
 
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) on Kaggle
 
---
 
*This project is part of my Data Science portfolio as I transition into tech. Feedback and suggestions are always welcome.*
