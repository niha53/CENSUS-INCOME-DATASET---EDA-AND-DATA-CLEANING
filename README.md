**Census Income Dataset – EDA and Data Cleaning**
**Project Overview**

This project focuses on performing Exploratory Data Analysis (EDA) and Data Cleaning on the Census Income Dataset (also known as the Adult dataset).
The goal is to understand the demographic factors that influence income levels and prepare the dataset for further modeling or machine learning tasks.
**Dataset Information**

**Dataset Name:** Census Income (Adult) Dataset
*Source:UCI Machine Learning Repository
 or Kaggle
**File Format:** .csv

**Description:**
The dataset contains demographic information of individuals and their income level (≤50K or >50K per year).

**Main Columns:**

age

workclass

education

education-num

marital-status

occupation

relationship

race

sex

capital-gain

capital-loss

hours-per-week

native-country

income (Target variable)

**Data Cleaning Steps**

Loaded dataset using pandas.

Checked missing values and handled them by:

Replacing '?' with NaN.

Imputing or removing rows with missing values.

Removed duplicates if any.

Standardized column names (converted to lowercase and replaced spaces with underscores).

Converted data types (e.g., age, hours-per-week → numeric).

Handled outliers using statistical methods (IQR or visualization-based detection).

Encoded categorical variables using label encoding or one-hot encoding (for model readiness).

Saved cleaned dataset as census_cleaned.csv.

**Exploratory Data Analysis (EDA)
**
Performed detailed EDA to understand data distribution and relationships.

Steps included:

Descriptive statistics (df.describe(), df.info()).

Univariate analysis:

Distribution of age, education, and hours-per-week.

Count plots for workclass, occupation, and income.

Bivariate analysis:

Relationship between education and income.

Effect of hours-per-week and age on income.

Correlation analysis:

Correlation heatmap of numeric variables.

Visualizations:

Used Matplotlib and Seaborn for bar plots, histograms, box plots, and heatmaps.

**Tools & Libraries Used**

Python 3.x

Jupyter Notebook

Pandas

NumPy

Matplotlib
