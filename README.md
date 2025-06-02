Titanic Dataset - Exploratory Data Analysis (EDA)
This repository contains a detailed exploratory data analysis (EDA) on the Titanic dataset. The analysis aims to uncover patterns, relationships, and key insights from the data that could help understand the factors affecting passenger survival during the Titanic disaster.

Objective
The main goal of this analysis is to explore the dataset visually and statistically. This helps in understanding the structure of the data, detecting missing values, identifying potential patterns, and building intuition for future predictive modeling tasks.

Dataset
The analysis is based on the Titanic test dataset (tested.csv), which includes information about passengers such as:

Survival status (Survived)

Passenger class (Pclass)

Name, Sex, Age

Number of siblings/spouses aboard (SibSp)

Number of parents/children aboard (Parch)

Fare paid

Other attributes relevant to the voyage

Key Analysis Steps
Data Loading and Basic Exploration

Loaded the dataset using pandas.

Viewed data types, basic statistics, and the first few rows.

Checked for and quantified missing values.

Univariate Analysis

Visualized the distribution of numerical features like Age using histograms.

Used count plots to analyze categorical features such as survival status and gender.

Bivariate and Multivariate Analysis

Compared survival rates between different genders.

Used boxplots to analyze the relationship between age and passenger class.

Created pair plots to observe relationships between features like Pclass, Age, Fare, and survival.

Correlation Analysis

Generated a correlation matrix heatmap to identify how different features are related numerically.

Highlighted strong and weak correlations between variables such as Fare, Age, and Pclass.

Insights Gained
Female passengers had a significantly higher survival rate than males.

Passengers in first class had better survival chances than those in second or third class.

Younger passengers were more likely to survive, especially children.

Fare showed some correlation with survival, indicating wealthier passengers had an advantage.

Missing values in the Age column were a notable issue that needs handling in preprocessing.

Tools and Libraries Used
Python

Pandas for data manipulation

Matplotlib and Seaborn for visualization

Jupyter Notebook for interactive analysis

How to Use
To run the notebook:

Make sure you have Python and Jupyter installed.

Install the required libraries: pandas, matplotlib, seaborn.

Open and run the notebook 123.ipynb from Jupyter.

Ensure the Titanic dataset file (tested.csv) is available in the correct path or update the path in the notebook accordingly.

Conclusion
This EDA provides a strong foundation for further machine learning or statistical modeling. By understanding the structure and patterns within the Titanic dataset, we’re better equipped to build models that can predict survival based on passenger information.
