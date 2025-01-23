# Capstone-Project
This project analyzes employee appraisal data to understand factors influencing appraisal percentages and build a predictive model. We'll examine relationships between various metrics like experience, ratings, and appraisal outcomes.

## Steps for Project:

### Step1: Importing DATA

### Step 2: Exploratory Data Analysis (EDA)

Distribution of each numerical variable (e.g., histograms, box plots).
Correlation matrix to understand the relationship between independent variables and the target.
Outlier detection in ratings and percentages.
Trends of appraisal percentages across various groups:
Do employees with higher personal ratings get higher appraisals?
Does company experience affect appraisals?
Missing value treatment (if applicable).

### Step 3: Feature Engineering

Normalize ratings (e.g., scale 1–10 data to match 1–5 scale).
Create interaction terms:
Interaction between Years_of_Experience and Emp_Rating.
Encode categorical data (if added later).

### Step 4: Model Development

Split the data into training and testing sets (e.g., 80–20 split).
Train and evaluate models such as:
Linear Regression

#### Questions:

Which model gives the best R² or RMSE score?
Does including interaction terms improve the model?
Evaluate feature importance (e.g., using SHAP or model-specific importance plots).

### Step 5: Model Evaluation

Compare models on validation data.
Check overfitting using metrics on train/test datasets.
Perform cross-validation for stability.

### Step 6: Predict Values on New Data

Use the best model to predict appraisals for a new set of employee data (to be simulated).

### Step 7: Business Insights

What are the most influential factors affecting appraisal percentages?
Are there patterns or biases in ratings?
Suggest recommendations for transparent appraisals.

#### Sample EDA Questions:

Are stakeholders’ ratings biased based on tenure or self-ratings?
Does experience always positively correlate with appraisal?

#### Modelling Questions:

What is the relationship between the appraisal percentage and employee ratings?
Can the model generalize predictions across multiple years?

#### Final Predictions:

Predict appraisals for a subset of employees.
