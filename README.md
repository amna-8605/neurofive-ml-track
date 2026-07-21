# Neurofive ML Track

This repository contains the weekly tasks completed during my Machine Learning Internship at **Neurofive Solutions**.

The project uses the Titanic dataset to learn the complete Machine Learning workflow, starting from Exploratory Data Analysis (EDA) to building and evaluating a Machine Learning model.

---

# Dataset

**Titanic - Machine Learning from Disaster (Kaggle)**

The objective is to analyze passenger information and predict whether a passenger survived the Titanic disaster.

---

# Task 1 - Exploratory Data Analysis (EDA):

## Objective
Perform Exploratory Data Analysis to understand the dataset before applying Machine Learning.

## Tasks Completed
- Loaded the Titanic dataset using Pandas
- Explored dataset using:
  - `head()`
  - `info()`
  - `describe()`
- Checked dataset shape
- Identified numerical and categorical columns
- Detected missing values
- Wrote a summary of findings

## Skills Learned
- Data loading with Pandas
- Dataset exploration
- Understanding data types
- Missing value analysis
- Exploratory Data Analysis (EDA)

---

# Task 2 - Data Cleaning & Visualization:

## Objective
Clean the dataset and create visualizations to better understand the data.

## Data Cleaning
- Filled missing values in the **Age** column using the median
- Filled missing values in the **Embarked** column using the mode
- Dropped the **Cabin** column because it contained a large number of missing values

## Outlier Detection
Detected outliers using a **boxplot** for numerical columns.

## Visualizations Created
- Histogram
- Boxplot
- Bar Chart
- Correlation Heatmap

## Key Observation
Based on the visualizations, passenger **Sex** appeared to have the strongest relationship with survival. Female passengers had a significantly higher survival rate than male passengers.

## Skills Learned
- Handling missing values
- Data cleaning
- Outlier detection
- Data visualization using Matplotlib and Seaborn
- Correlation analysis

---

# Task 3 - Titanic Survival Prediction:

## Objective
Build a Machine Learning model to predict passenger survival.

## Preprocessing
- Encoded categorical columns using `pd.get_dummies()`
- Selected input features and target variable
- Split the dataset into training and testing sets using `train_test_split()`

## Machine Learning Model
- Logistic Regression

## Model Evaluation
- Accuracy Score
- Confusion Matrix

### Final Accuracy
81.56%

## Confusion Matrix
The confusion matrix shows:
- Correctly predicted survivors
- Correctly predicted non-survivors
- Incorrect predictions made by the model

It helps evaluate the performance of the classifier beyond accuracy alone.

## Skills Learned
- Feature encoding
- Train/Test split
- Logistic Regression
- Classification
- Model evaluation
- Accuracy Score
- Confusion Matrix

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git
- GitHub

---

# Repository Structure

```
neurofive-ml-track/
│
├── Titanic_EDA.ipynb
├── train.csv
├── test.csv
├── README.md
```

---

# Future Improvements

- Try Decision Tree Classifier
- Random Forest Classifier
- Feature Engineering
- Hyperparameter Tuning
- Compare multiple Machine Learning models

---


---

# Task 4 - House Price Prediction using Linear Regression

## Objective
Build a Linear Regression model to predict house prices using the California Housing dataset.

## Steps Performed
- Loaded the California Housing dataset
- Selected important features affecting house prices
- Split the dataset into training and testing sets
- Trained a Linear Regression model
- Evaluated the model using RMSE and R² Score
- Visualized Actual vs Predicted house prices using a scatter plot

## Skills Learned
- Regression
- Linear Regression
- Feature Selection
- Train-Test Split
- RMSE
- R² Score
- Model Evaluation

## Final Results
- **RMSE:** 0.81
- **R² Score:**0.49

## Author

**Amna Shahid**

Machine Learning Intern at Neurofive Solutions
