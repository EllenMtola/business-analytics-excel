# Restaurant Tips Prediction Using Excel

## Overview

This project demonstrates how Microsoft Excel can be used to build a predictive model for estimating restaurant tips based on customer and dining characteristics. The project covers the complete data analytics process, including data cleaning, feature engineering, correlation analysis, regression modeling, and model evaluation.

Using Excel's built-in functions and the Data Analysis ToolPak, the project predicts customer tip amounts and evaluates the accuracy of the model using Root Mean Square Error (RMSE).

---

## Project Objectives
- Clean and prepare the restaurant tips dataset.
- Identify independent and dependent variables.
- Encode categorical variables into numeric values.
- Analyze relationships between variables using correlation analysis.
- Build a Multiple Linear Regression model.
- Predict restaurant tip values.
- Compare predicted and actual tips.
- Evaluate model accuracy using RMSE.
- Visualize the results with charts.
---

## Dataset Information
The dataset contains customer dining information, including:
- **Sex**
- **Smoker**
- **Day**
- **Time**
- **Party Size**
- **Total Bill**
- **Tip (Target Variable)**
---

## Tools Used

- Microsoft Excel
- Excel IF Function
- CORREL Function
- Data Analysis ToolPak (Regression)
- PivotTables
- PivotCharts
- Conditional Formatting
- Scatter Charts
- Line Charts
---

## Project Workflow

### 1. Data Cleaning
- Removed missing values
- Removed duplicate records
- Verified data quality

### 2. Feature Engineering
Categorical variables were converted into numeric values using IF functions.
Examples:

- Male = 1, Female = 0
- Yes = 1, No = 0
- Lunch = 0, Dinner = 1
- Thur = 1, Fri = 2, Sat = 3, Sun = 4

### 3. Correlation Analysis

Calculated correlation coefficients between each independent variable and the Tip column using the `CORREL()` function to identify the strongest predictors.

### 4. Regression Model

Built a Multiple Linear Regression model using Excel's Data Analysis ToolPak to predict restaurant tips.

### 5. Model Evaluation

Compared predicted tip values with actual tip values and calculated the Root Mean Square Error (RMSE) to measure the model's prediction accuracy.

---

## Dashboard & Visualizations

The project includes visualizations such as:

-  Actual Tips vs Predicted Tips
-  Total Bill vs Tip Scatter Plot
-  Correlation Analysis
-  Average Tip by Day
-  Average Tip by Time
-  Average Tip by Gender
-  Regression Trendline

---

## Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Correlation Analysis
- Regression Analysis
- Predictive Analytics
- Model Evaluation
- Data Visualization
- Business Analytics
- Microsoft Excel

---

##  Results

The regression model successfully predicts restaurant tip amounts using customer and dining characteristics. Correlation analysis identified the variables that have the strongest influence on tipping behavior, while RMSE was used to evaluate the prediction accuracy of the model.

This project demonstrates that Microsoft Excel can be used to perform end-to-end predictive analytics without requiring programming languages.

---
Ellen Mtola**

Aspiring Data Analyst | Excel | Power BI | SQL | Python | Data Visualization
