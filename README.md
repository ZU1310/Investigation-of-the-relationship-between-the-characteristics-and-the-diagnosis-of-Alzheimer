# Investigation-of-the-relationship-between-the-characteristics-and-the-diagnosis-of-Alzheimer
Logistic Regression Has been implemented on the Alzheimer Dataset.

In the world, Alzheimer's disease (AD), a neurodegenerative condition, is the most prevalent 
cause of dementia and the sixth greatest cause of mortality. Memory loss that worsens with 
time, cognitive impairment, and behavioural abnormalities are the disease's hallmarks. The 
present therapies for AD simply alleviate symptoms; there is no known cure for the 
condition.
This study identified risk factors for AD using descriptive statistics, clustering, and logistic 
regression, which is presented in this report. An analysis of 317 individuals' data revealed 
that older age, male gender, lower socioeconomic level, lower educational attainment, and 
lower cognitive test scores were all linked to a higher risk of AD.
According to the study's findings, there are a number of AD risk factors that can be changed. 
A reduction in the prevalence of AD and an improvement in the quality of life for those who 
have the illness are both possible outcomes of interventions that focus on these risk factors.

## Methods

Here is a detailed summary of the methods and analysis steps from the report on investigating Alzheimer's disease risk factors:

## Data Loading and Preparation

- The dataset is loaded into R using read.csv()
- Missing values are removed with na.omit() 
- Categorical columns like gender are converted to numeric formats
- Invalid rows like 'Converted' are removed

## Exploratory Data Analysis 

- Summary statistics generated to describe all variables
- Visualizations created:
  - Boxplot for age vs disease group
  - Bar plot for SES vs cognitive score

## Clustering Analysis

- K-means clustering applied with k=2 to find natural groupings in data
- Data preprocessed by converting categorical disease label to numeric
- Cluster plot generated to visualize clustering results

## Logistic Regression 

- Multiple logistic regression used to predict disease status from risk factors
- Two models created - one with all variables, one with selected features
- Model accuracy checked, plots generated to assess fit
- Feature selection methods like stepwise used to reduce variables 

## Conclusions

- Key risk factors like age, gender, SES identified through analysis
- Limitations highlighted like small sample size

## In summary, the analysis follows a standard machine learning workflow - data preprocessing, exploratory analysis, clustering, predictive modeling with logistic regression, model evaluation and feature selection. The report highlights the important risk factors found while also noting limitations in the data and methodology. The steps could serve as a template for a typical machine learning analysis.
