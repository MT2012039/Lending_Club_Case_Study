# Lending_Club_Case_Study
Case study of Lending club for Upgrad course

# Steps involved in the case study

1) Cleaning of the data set
2) Analyse the cleaned dataset using Univariate Analysis and get Key insights into the independent variables
3) Analyse the cleaned dataset using Bivaritae analysis and find the key relations and insight from 2 variables
4) Added correlation matrix for numerical variables and analysed the key relations among multiple variables using heatmap

#Cleaning data set

1)Removed all columns which has more than 50% missing data
2)Removed all columns which has Null or Single unique values
3)Removed all Null values by taking informed decision for each columns
4)Converted date fields to datetime
5)Converted rate fields (with %) to integer
6)Converted few categorical columns like emp_length with custom values for analysis
7)Created derived columns year and month from payment dates for segmented analysis

#Univariate Analysis

1)Analysis of quantitative variables using boxplot.Cleaning of outliers in few cases (like annual income and interest rates)
2)Univariate analysis of unordered categorical variables using histogram and bar plots
3)Univariate analysis of ordered categorical variables using hist plot
4)Segmented analysis

#Bivariate analysis

1)Analysis of Loan status based on different categorical variables
2)Use of graphical representations like histplot,barplot,boxplots for clarity in analysis
3)Getting essential insights into the data and relation from the data using the analysis
4)Generating the corelation plot on all numerical variables
5)Finding essential insights into the correlation of multiple variables using heatmap 
