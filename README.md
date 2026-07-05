# Medical Students' Mental Health and Burnout Analysis
How do demographics and health traits predict mental health outcomes among Swiss medical students?

## Project Overview

This project explores the relationship between empathy, mental health, and burnout among medical students in Switzerland.

The analysis focuses on understanding demographic patterns, identifying relationships between psychological measures, and preparing the data for predictive machine learning models. The project includes exploratory data analysis (EDA), data preprocessing, feature engineering, and predictive modeling.

## Objectives

The objectives of this project are to:

- Explore the demographic characteristics of the participants.
- Analyze the distribution of mental health and empathy scores.
- Investigate relationships between burnout, depression, anxiety, empathy, and other variables.
- Identify important features associated with burnout.
- Prepare the dataset for machine learning models.
- Compare the performance of multiple classification models.

## Dataset

The dataset contains survey responses from medical students in Switzerland, including:

- Demographic information
- Academic information
- Empathy scores
- Depression scores
- Anxiety scores
- Burnout measures
- Psychological distress indicators

Source:
[Kaggle Dataset Link](https://www.kaggle.com/datasets/thedevastator/medical-student-mental-health/data?select=Data+Carrard+et+al.+2022+MedTeach.csv)


## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Engineering
5. Correlation Analysis
6. Machine Learning
7. Model Evaluation

## Data Preprocessing

The following preprocessing steps were performed:

- Renamed columns for readability
- Mapped categorical variables to descriptive labels
- Checked missing values
- Removed duplicate records
- Investigated outliers
- Encoded categorical variables
- Grouped minority language categories for machine learning
- Scaled numerical features where required

## Exploratory Data Analysis

The exploratory analysis included:

- Distribution of demographic variables
- Distribution of psychological scales
- Burnout across demographic groups
- Anxiety across demographic groups
- Depression across demographic groups
- Correlation analysis
- Missing value analysis
- Outlier detection

## Key Findings

- Burnout was highest among students in the early years of medical school.
- Female students showed slightly higher burnout and anxiety scores.
- Younger students generally experienced higher levels of burnout.
- Strong positive correlations were observed between depression, anxiety, and burnout.
- Empathy measures showed weaker relationships with burnout than mental health variables.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Collab

## Contributors

This project was completed as coursework at the University of Oulu by a team of three students.

**Student 1: Fatima Olasunkanmi-Ojo:**
Data understanding and column 
renaming, including the classification of variables into 
categorical and numeric types to support correct analysis. 
Distribution analysis was performed using bar charts, while 
box plot analysis was used for key mental health outcomes 
(depression, anxiety, and burnout). These visuals formed the 
foundation of the exploratory data analysis (EDA).

**Student 2: Shalini Singh:**
IQR outlier detection across all 18 variables, 
and carried out data integrity checks, including auditing and 
validating mature-student outliers, language consolidation 
from 40+ codes to 4 groups, validation via depression box 
plots, and production of the correlation matrix and scatter 
plot. Additionally, managed administrative tasks, including 
coordinating team activities and maintaining clear 
communication among group members.

**Student 3: Mahya Ehsanimehr:**
ML implementation, one-hot encoding, 
75/25 split, StandardScaler pipeline, all five classifiers for 
RQ1-3, grid search, SMOTE experiments, multi-output 
classifier, and classifier chain for burnout.
