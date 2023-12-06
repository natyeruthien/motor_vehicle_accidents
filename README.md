# Predicting Motor-vehicle Accidents

## Project Overview
This project explores the patterns and dynamics of car accidents across the United States, focusing on their impact on traffic congestion and correlation with various factors, particularly weather conditions. We aim to understand the prevalence and severity of accidents in different time zones, especially in the Eastern US, and develop both multi-class and binary classification models for analysis.

### Key Objectives
- Explore relationships between car accidents, traffic congestion, and weather conditions across the U.S.
- Develop multi-class and binary classification models to predict accident severity.
- Analyze factors impacting road safety and traffic management.

## Dataset
Description of the dataset including time, location, weather conditions, and severity levels.

## Methodology
- **Data Preprocessing**: Involved standardizing features, handling missing values, feature selection, and removing extreme outliers to ensure data quality and consistency.
- **Exploratory Data Analysis (EDA)**: Examining patterns in accidents across time zones and under various weather conditions.
- **Model Development**: Building both multi-class and binary classification models using Logistic Regression, Random Forest, Decision Tree, Naïve Bayes.
- **Evaluation**: Using accuracy, ROC AUC for One-vs-Rest (OvR) and One-vs-One (OvO) approaches to assess model performance.

## Results
Our study reveals that extreme weather conditions do not significantly correlate with accident frequency, suggesting the influence of other factors. Particularly, the exact location, which was not available in our dataset, could be a significant factor. The models offer insights into predicting and classifying accident severity, highlighting the complexities and challenges in enhancing road safety and traffic management.
## Limitations and Future Work
The study recognizes limitations such as severity level imbalance and non-causal variables, indicating the need for more detailed data. Future research should focus on enhancing the dataset and refining the models.

## Tools and Technologies
- **Language**: Python
- **Libraries/Frameworks**: sklearn, pandas, numpy, matplotlib, seaborn
