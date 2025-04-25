# Cardiovasculardisease_prediction
# Demographics and Lifestyle Factors in Relation to Cardiovascular Risk

## Project Overview
This repository contains a machine learning project that examines the relationship between demographic factors, lifestyle choices, and cardiovascular disease risk. The research utilizes statistical analysis and predictive modeling to identify significant risk factors and develop a machine learning model capable of predicting cardiovascular disease presence.

## Contributors
- Daniel Cheruiyot (dcheriu@iu.edu)
- Parvathi Dandibhotla (padandi@iu.edu)
- Oludare Odewenwa (oodewenw@iu.edu)
- Ramya Keerthi Majji (rmajji@iu.edu)

## Introduction
Cardiovascular disease (CVD) has emerged as a leading global health concern, significantly impacting public health and healthcare systems worldwide. Millions of individuals are affected by CVD each year, making it one of the most prevalent global health issues.

### Aim
The primary goal of this study is to thoroughly examine the connections between various demographic and lifestyle factors and build a machine learning model which can predict the presence or absence of cardiovascular diseases.

## Risk Factors
The project examines several major factors influencing cardiovascular disease occurrence:
- Blood pressure
- Cholesterol levels
- Glucose levels
- Smoking habits
- Alcohol consumption
- Physical activity

## Hypothesis
### Null Hypothesis (H0)
The null hypothesis states that there is no significant combined effect of age, gender, blood pressure, cholesterol levels, glucose levels, smoking status, alcohol intake, and physical activity on the presence of cardiovascular disease in the studied population.

### Alternative Hypothesis (H1)
The alternative hypothesis proposes that there is a significant combined effect of age, gender, blood pressure, cholesterol levels, glucose levels, smoking status, alcohol intake, and physical activity on the presence of cardiovascular disease in the studied population. It suggests that these factors, when considered together, play a role in the presence or absence of cardiovascular disease.

## Methodology
The project followed these key steps:
1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis
2. **Storage and Extraction**: Organizing data for efficient access
3. **Data Description**: Understanding the dataset's characteristics
4. **Statistical Analysis**: Applying statistical tests to identify correlations
5. **Data Visualization**: Creating visual representations to understand patterns
6. **Machine Learning**: Building predictive models
7. **Hypothesis Testing**: Validating research hypotheses

## Dataset
- Source: Heart Disease Dataset by Yasser H on Kaggle
- Size: 68,205 rows and 17 columns
- Data imported from MyPHP admin

## Data Processing
### Data Preparation
- Checked for null values and duplicates
- Dataset contained no null or duplicate values
- Performed outlier detection and treatment for BMI using the IQR method

### Exploratory Data Analysis (EDA)
- Utilized descriptive statistics to summarize and explore data distributions
- Created visualizations including bar charts, histograms, and pie charts
- Analyzed distributions of various demographic factors

### Normality Testing
- Conducted visual assessment using Q-Q plots and histograms
- Performed Shapiro-Wilk test for quantitative assessment
- Determined appropriate statistical tests based on data distribution

## Statistical Analysis
### Tests Performed
- **Mann-Whitney U Test**: Applied for non-parametric numerical data
- **Chi-square Tests**: Used for categorical variables
- **Spearman Correlation Test**: Employed for ordinal categorical data
- **Logistic Regression Test**: Used to examine associations between multiple variables and the binary outcome

## Machine Learning Models
Three different machine learning models were built and evaluated:

### Logistic Regression Model
- Achieved approximately 70% accuracy
- Data split: 80% training, 20% testing
- Included confusion matrix and ROC curve analysis

### K-Nearest Neighbor Model
- Achieved approximately 66% accuracy

### Random Forest Model
- Achieved approximately 64% accuracy

## Results and Conclusions
- Statistical evidence was sufficient to reject the null hypothesis
- Found significant correlations between demographic/lifestyle factors and cardiovascular disease
- The logistic regression model performed best with 70% accuracy
- Key risk factors identified: age, blood pressure, cholesterol levels, glucose levels, smoking status, alcohol intake, and physical activity

## Limitations
- Data quality and availability may impact model accuracy and generalizability
- The project relied on a single dataset, limiting applicability to diverse populations
- Machine learning model complexity may hinder interpretation of relationships between variables

## References
1. Adhikary, D. K., Barman, S., Ranjan, R., & Stone, H. (2022). A Systematic review of major cardiovascular risk factors: a growing global health concern. Cureus. https://doi.org/10.7759/cureus.30119
2. CDC. Know your risk for heart disease. 2019. Available from: https://www.cdc.gov/heartdisease/risk_factors.htm
3. Damen, J. A., et al. (2016). Prediction models for cardiovascular disease risk in the general population: systematic review. BMJ, i2416. https://doi.org/10.1136/bmj.i2416
4. Tran, D.M.T., et al. (2021). Risk factors associated with cardiovascular disease among adult Nevadans. PLOS ONE, 16(2), e0247105. https://doi.org/10.1371/journal.pone.0247105
5. D. Medh, "Descriptive Statistics in Python," [Online]. Available: https://dipankarmedh1.medium.com/descriptive-statistics-in-python-2f6f725739b1
6. Toward Data Science. "Hypothesis Testing with Python: Step-by-Step Hands-on Tutorial with Practical Examples," [Online]. Available: https://towardsdatascience.com/hypothesis-testing-with-python-step-bystep-hands-on-tutorial-with-practical-examples-e805975ea96e
