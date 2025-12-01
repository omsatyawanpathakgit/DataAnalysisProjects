# Titanic Survival Prediction ML Project


## Overview

This project is a complete Machine Learning analysis on the Titanic dataset. It involves data exploration, preprocessing, feature engineering, model training, and evaluation to predict passenger survival based on various features like age, sex, class, etc. The project is implemented in Python using libraries such as Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.



## Dataset

The dataset used in this project is "train.csv" obtained from here: https://www.kaggle.com/code/mrisdal/exploring-survival-on-the-titanic/input?select=train.csv

It contains information about 891 passengers. Key features include:

### Data Dictionary

| Variable   | Definition                          | Key                                      |
|------------|-------------------------------------|------------------------------------------|
| survival  | Survival                            | 0 = No, 1 = Yes                          |
| pclass    | Ticket class                        | 1 = 1st, 2 = 2nd, 3 = 3rd                |
| sex       | Sex                                 |                                          |
| Age       | Age in years                        |                                          |
| sibsp     | No. of siblings / spouses aboard the Titanic | |
| parch     | No. of parents / children aboard the Titanic | |
| ticket    | Ticket number                       |                                          |
| fare      | Passenger fare (in British pounds (£)) |                                       |
| cabin     | Cabin number                        |                                          |
| embarked  | Port of Embarkation                 | C = Cherbourg, Q = Queenstown, S = Southampton |

- **Source**: The dataset is from Kaggle's Titanic competition.
- **Rows**: 891
- **Columns**: 12
- **Missing Values**: Handled for Age (filled with median), Embarked (filled with mode), and Cabin (dropped).


## Project Structure

```
titanic-ml-project/
├── Complete Titanic ML Analysis.ipynb  # Main Jupyter Notebook
├── Complete Titanic ML Analysis.pdf     # PDF export of the notebook
├── train.csv                            # Titanic dataset
├── headerImage.png                      # Header image used in the notebook
├── ending_image.jpg                     # Ending image used in the notebook
├── requirements.txt                     # Python dependencies
└── README.md                            # This file (explaining about this project)
```

## Data Preprocessing

- **Handling Missing Values**:
  - Age: Filled with median value.
  - Embarked: Filled with mode (most frequent value).
  - Cabin: Dropped due to following reasons:
        - high missing values (687 out of 891).
        - this column would also not be useful for ML related tasks.

- **Feature Engineering**:
  - These features are encoded so that we can easily apply machine-learning on it.
     a- sex
     b- embarkation-point
  - These new features are created out of the following:
     a- number of family members created from summing up no. of siblings , no. of spouse (aks SibSp)  and no. of parents (And/or) children (aka Parch).
  - Dropped irrelevant columns like PassengerId, Name, Ticket.



## Exploratory Data Analysis (EDA)

- **Basic Inspections**: Checked shape (891 rows, 12 columns), data types, and null values.
- **Visualizations**: 
  - Survival comparison by sex, class and etc.
  - Correlation heatmap.

Some findings done at the beginning:
- No. of rows: 891
- No. of columns: 12
- Missing values before handling: Age (177), Cabin (687), Embarked (2)

## Model Training and Evaluation

- **Models Used**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)

- **Train-Test Split**: 70% of data was used for training and the remaining 30% for testing.
- **Evaluation Metrics**: Accuracy, Confusion Matrix.




## Results observed (like from the above code snippet)

- **Model Performance** (example results; run notebook for exact):
  - KNN: Accuracy ~73%
  - CONCLUSION OF THIS KNN MODEL: A Female Person of 38 years of age and with an income of 71 pounds (British pounds) is likely to survive.
 




## Author

Prepared by:  
- **Name**: Om Satyawan Pathak  
- **Contact**: omsatyawanpathakwebdevelopment@gmail.com (or) omsatyawanpathakgit@gmail.com  

Feel free to contact me for any further clarifications.
