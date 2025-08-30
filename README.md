🛳️ Titanic Survival Exploratory Data Analysis
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset from Kaggle
.
The goal is to understand the relationship between passenger attributes and survival rate, uncovering factors that influenced survival during the disaster.

🎯 Objectives

Clean and prepare the dataset for analysis.

Perform univariate and bivariate analysis.

Visualize patterns in age, gender, passenger class, and embarkation port.

Highlight survival trends using plots and summary statistics.

📂 Dataset

Source: Kaggle Titanic Dataset

Columns used:

Survived – Survival (0 = No, 1 = Yes)

Pclass – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Sex – Passenger gender

Age – Passenger age

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

🛠️ Steps Performed

Data Wrangling

Checked for missing values.

Filled missing Age with median.

Filled missing Embarked with most frequent value.

Created new features:

FamilySize = SibSp + Parch + 1

IsAlone = 1 if FamilySize == 1 else 0

Exploratory Data Analysis (EDA)

Univariate Analysis: Age distribution, Fare distribution, class/gender breakdown.

Bivariate Analysis: Survival rates by class, gender, embarkation port, family size.

Visualizations

Bar plots: Survival by sex, class, and embarkation port.

Histograms: Age and fare distributions.

Boxplots: Fare by class, Age by survival, Fare by survival.

📊 Key Insights

Gender: Females had a much higher survival rate than males.

Class: 1st class passengers were more likely to survive than 2nd and 3rd class.

Age: Children had a slightly higher survival rate compared to adults.

Fare: Passengers who paid higher fares had better survival chances.

Family: Very large families had lower survival rates, while small families fared better than those alone.

📸 Sample Visualizations

Survival counts (Survived vs Not Survived)

Survival rate by Sex

Survival rate by Passenger Class

Age distribution of survivors vs non-survivors

Fare distribution across classes

📦 Requirements

Install dependencies:

pip install pandas numpy matplotlib





Launch Jupyter Notebook:

jupyter notebook


Open Titanic_EDA.ipynb and run the cells.

📌 Learning Outcomes

Hands-on practice in data wrangling and EDA.

Improved understanding of univariate & bivariate analysis.

Ability to visualize insights using bar plots, histograms, and boxplots.
