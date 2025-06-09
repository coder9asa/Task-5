# Task-5
Exploratory Data Analysis (EDA)

---

## 📌 Objective

The goal of this analysis is to explore the Titanic dataset, understand key survival factors, and generate actionable insights based on socio-demographic variables.

---

## 🧾 Dataset Overview

- **Source**: Kaggle Titanic: Machine Learning from Disaster  
- **Rows**: 891 passengers  
- **Columns**: 12 features  
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

Key columns analyzed include:
- `Pclass`: Ticket class
- `Sex`: Gender
- `Age`: Age in years
- `Fare`: Ticket fare
- `Embarked`: Port of embarkation
- `SibSp`, `Parch`: Family aboard

---

## 🔍 Key Analyses

- **Missing Value Treatment**: Summary of null values and imputation strategies
- **Univariate Analysis**: Age, Fare, Pclass, Sex
- **Bivariate/Multivariate Analysis**: Survival relationships with gender, class, fare, family size
- **Visualizations**:
  - Histograms & KDE plots
  - Boxplots
  - Correlation heatmap
  - Survival vs. Age & Fare scatter plots
  - Class-wise age distributions

---

## 💡 Insights Summary

- **Women had higher survival rates** than men (correlation = 0.54).
- **1st Class passengers** were significantly more likely to survive than 3rd class.
- **Higher fares** correlated with better survival chances.
- **Most passengers were young adults (20–40)**; children had relatively better chances in lower classes.
- **77% of Cabin data is missing**, limiting deck-level survival insights.

