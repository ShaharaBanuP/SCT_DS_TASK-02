Titanic Dataset Exploratory Data Analysis (EDA)

Project Overview
This project performs an Exploratory Data Analysis (EDA) on the famous Titanic dataset to uncover key insights about passengers and factors affecting survival. The analysis focuses on understanding data distributions, relationships between variables, and identifying outliers to prepare the dataset for further modeling.

Key Steps
Data Understanding & Cleaning:
Explored the dataset structure, handled missing values, and ensured correct data types.

Bivariate Analysis:
Analyzed relationships between important variables, such as Passenger Class (Pclass) vs Fare and Age vs Passenger Class, to understand socio-economic and demographic patterns.

Correlation Analysis:
Computed correlation matrix for all numerical features to detect linear relationships. Found moderate correlation between family-related features (SibSp and Parch), while other features showed weak correlations.

Outlier Detection & Treatment:
Used boxplots and the Interquartile Range (IQR) method to identify and remove outliers in continuous variables like Fare and Age to improve data quality.

Insights
Higher-class passengers paid significantly higher fares and tended to be older.

Family size variables (SibSp, Parch) are moderately correlated, reflecting family groups onboard.

Outlier removal helped reduce skewness in fare and age distributions, preparing the data for reliable modeling.

Tools & Libraries
Python (Pandas, NumPy)

Visualization: Seaborn, Matplotlib


