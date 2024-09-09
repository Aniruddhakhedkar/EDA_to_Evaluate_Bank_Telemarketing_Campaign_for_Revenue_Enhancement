# Exploratory_Data_Analysis_Using_Python_Project_2-

## Problem Description

The bank aims to enhance its revenue by conducting a cost-efficient telemarketing campaign for term deposits among existing customers. Term deposits, fixed investments with predetermined interest rates, serve to foster long-term customer relationships. The objective is to conduct an end-to-end Exploratory Data Analysis (EDA) on the campaign dataset, identifying patterns and providing insights to improve the positive response rate. 
The analysis will involve examining customer demographics, temporal trends, and other factors influencing the success of the campaign, ultimately offering recommendations for targeted improvements in the bank's marketing strategy.


## Objectives_of_the_Analysis-

1. Understanding the Dataset-
Load and scrutinize the dataset to comprehend its structure, encompassing columns and data types.
Inspect for any instances of missing values, outliers, or data inconsistencies.

2. Descriptive Statistics-
Derive summary statistics (mean, median, standard deviation) for relevant columns.
Examine the distribution of the target variable, indicating responses to the term deposit campaign.

3. Univariate Analysis-
Examine the distribution of individual key features, such as age, balance, and call duration.
Employ visual aids like histograms, box plots, and kernel density plots to discern patterns and outliers.

4. Bivariate Analysis-
Evaluate the relationship between independent variables and the target variable.
Analyze how features like age, job type, education, marital status, etc., associate with the success of the term deposit campaign, using visualizations like bar charts, stacked bar charts, and heat maps.

5. Categorical Variables Analysis-
Investigate the distribution of categorical variables such as job type, education, and marital status.
Assess the impact of these categorical variables on the campaign's success through visualizations like bar charts.

6. Temporal Analysis-
Investigate temporal patterns in the success of the campaign over time.
Analyze if specific months or days exhibit superior campaign performance.

7. Feature Engineering-
Introduce new features that may enhance prediction, such as creating age groups or income categories.
Apply encoding techniques to transform categorical variables if necessary.

8. Correlation Analysis-
Examine correlations between independent variables to identify multicollinearity.
Evaluate how correlated features may influence the target variable.

9. Outlier Detection and Handling-
Identify and rectify outliers that could impact the analysis and predictions.

## EDA_Methodology_Employed- 

1) Cleaning the data, and assigning the proper data type to the variables
2) Descriptive statistics
3) Removal of duplicates
4) Handling missing values (Imputation)
5) Outlier removal
6) Understanding the collinearity between independent variables
7) Determination of correlationship between independent and dependent variable
8) Storage of cleaned data in a new excel file and EDA report preparation

## Python_Libraries_Used-

1)NumPy
2)Pandas
3)Matplotlib
4)Seaborn
5)Scipy

## Findings-

1. Problem with Customer Targeting-
This campaign is offering/targeting its product to the customers with diversified economical & social background, and demographics. This has led to the problem of one fit for all. 

2. Communication problem-
Call_Duration_Min_1[(Median<<<<Mode)] & Call_Duration_Min_1 is directly proportional to the positive response from customers. 
This indicates that, for some of the calls the call duration is very less, indicating problem with the communicator/communication channel.

3. Improper understanding of high prospect customer segment by campaigner- 
The campaigner might not be aware about the customers that are expected to open the term-deposit account easily, before the start of campaign. For example- Financial condition of the potential customer, their occupation which are more likely to open the term-deposit account.

## Recommendation-

1. Ask the marketing team to finetune the customer segment they are intending to target and provide same to the team responsible for running the campaign. [To improve the targeting]

2. Improve the communication channel (Digital channels & Employee training).

3. Remapping the product’s market relevance, as for some of the ideal potential customers the offered product is not catering their new needs. [To map potential change occurred in customers’ requirements]

