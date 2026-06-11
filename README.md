# Marketing-Mix-Modelling
# 📊 Marketing Mix Modeling (MMM) with Budget Optimization

## 📌 Project Overview

This project develops an Advanced Marketing Mix Model (MMM) to measure the impact of multiple marketing channels on sales and provide data-driven budget allocation recommendations.

The model uses marketing spend data from traditional and digital channels, applies marketing-specific transformations such as Adstock and Saturation, and leverages machine learning techniques to estimate channel contributions and optimize future marketing investments.

---

## 🎯 Business Problem

Marketing teams invest across multiple channels such as:

- TV Sponsorships
- TV Cricket Campaigns
- TV Run-of-Network (RON)
- Radio
- Newspapers (NPP)
- Magazines
- Out-of-Home (OOH)
- Social Media
- Programmatic Advertising
- Display Advertising
- Search Marketing
- Native Advertising

The challenge is to determine:

- Which channels contribute most to sales?
- Which channels generate the highest ROI?
- How should future budgets be allocated?
- What sales impact can be expected from budget reallocation?

---

## 📂 Dataset

### Variables

#### Target Variable
- Sales

#### Marketing Channels
- TV Sponsorships
- TV Cricket
- TV RON
- Radio
- NPP
- Magazines
- OOH
- Social
- Programmatic
- Display_Rest
- Search
- Native

#### Time Variable
- Weekly/Monthly marketing observations

---

## 🛠️ Methodology

### 1. Data Preparation

- Missing value handling
- Date formatting
- Duplicate removal
- Exploratory Data Analysis (EDA)

### 2. Marketing Transformations

#### Adstock Transformation
Captures delayed advertising effects.

#### Saturation Transformation
Models diminishing returns using logarithmic transformation.

### 3. Model Development

Three models were compared:

- Linear Regression
- Ridge Regression
- Lasso Regression

Ridge Regression was selected due to multicollinearity among marketing channels.

### 4. Model Evaluation

Metrics used:

- R² Score
- Mean Absolute Error (MAE)

### 5. Channel Contribution Analysis

Estimated contribution of each marketing channel using model coefficients.

### 6. Budget Optimization

Scenario simulations were conducted to evaluate:

- TV-to-Digital budget shifts
- Search budget increases
- High-performing channel investments

---

## 📈 Project Workflow

Data Collection
↓
Data Cleaning
↓
EDA
↓
Adstock Transformation
↓
Saturation Transformation
↓
Feature Scaling
↓
Regression Modeling
↓
Model Evaluation
↓
Channel Contribution Analysis
↓
ROI Analysis
↓
Budget Optimization
↓
Power BI Dashboard

---

## 📊 Power BI Dashboard

### Page 1 – Executive Overview
- Total Sales
- Total Spend
- ROI
- Model Accuracy

### Page 2 – Channel Performance
- Channel Contribution
- Spend Distribution
- ROI by Channel
- Spend vs Impact Analysis

### Page 3 – Model Performance
- Actual vs Predicted Sales
- Residual Analysis
- Model Accuracy Metrics

### Page 4 – Budget Optimization
- Scenario Analysis
- Incremental Lift
- Recommended Budget Allocation
- ROI Impact

---

## 📊 Key Insights

- Digital channels generated higher incremental sales lift than several traditional channels.
- Search and Programmatic advertising demonstrated strong ROI performance.
- Adstock effects highlighted delayed impacts of media spending.
- Budget reallocation scenarios improved projected sales outcomes.

---

## 💻 Technologies Used

### Programming
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Visualization
- Power BI

### Modeling Techniques
- Adstock Modeling
- Saturation Modeling
- Linear Regression
- Ridge Regression
- Lasso Regression

---


---

## 🚀 Business Value

This project demonstrates how Marketing Mix Modeling can support:

- Marketing budget optimization
- Channel effectiveness measurement
- ROI improvement
- Strategic marketing planning
- Data-driven decision-making

---

## 👩‍💻 Author

Yamini

MSc Business Analytics

Queen's University Belfast

Interested in Marketing Analytics, Business Intelligence, Machine Learning, and Data-Driven Decision Making.
