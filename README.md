# Advanced Data Science Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Data Understanding](#data-understanding)
4. [Data Preparation](#data-preparation)
5. [Data Analysis](#data-analysis)
6. [Data Exploration](#data-exploration)
7. [Conclusion](#conclusion)
8. [References](#references)

## Introduction

This project is part of the Applied Data Science module at London Metropolitan University, aimed at analyzing a dataset containing salaries of data science professionals from 2020 to 2023. The analysis focuses on various aspects such as salary trends, job titles, experience levels, and more.

## Objectives

The objectives of this data analysis project include:

- Analyzing salary trends over the years.
- Evaluating the impact of experience levels on salaries.
- Examining job titles and their corresponding salaries.
- Detecting and handling outliers in the salary data.
- Visualizing data distribution using various graphical representations.

## Data Understanding

### Dataset Description

The dataset contains information about salaries of data science professionals. It includes the following columns:

- **work_year**: The year the data was recorded.
- **salary**: The salary amount in the local currency.
- **salary_in_usd**: The salary amount converted to USD.
- **remote_ratio**: The percentage of remote work.
- **experience_level**: The level of experience of the employee.
- **employment_type**: The type of employment.
- **job_title**: The job title of the employee.
- **salary_currency**: The currency in which the salary is paid.
- **employee_residence**: The country of residence of the employee.
- **company_location**: The location of the company.
- **company_size**: The size of the company.

### Data Overview

- **Entries**: 3,755
- **Columns**: 11

## Data Preparation

### Loading Data

The first step in the analysis process is to load the data using Python's Pandas library.

### Removing Unnecessary Columns

Removing columns that are not needed for the analysis.

### Handling Missing Values

Identifying and handling missing values in the dataset.

### Checking for Duplicate Values

Checking for and handling duplicate values in the dataset.

### Viewing Unique Values in Columns

Counting the unique values in each column.

## Data Analysis

### Summary Statistics

Calculating various summary statistics to understand the dataset better.

- **Sum**: Total of all salary values.
- **Mean**: Average salary.
- **Standard Deviation**: Measure of the amount of variation in salary.
- **Skewness**: Measure of the asymmetry of the salary distribution.
- **Kurtosis**: Measure of the "tailedness" of the salary distribution.

### Correlation Analysis

Calculating the correlation between different variables to understand their relationships.

## Data Exploration

### Top 15 Job Titles

Analyzing the top 15 job titles in terms of frequency.

### Job Titles with the Highest Salaries

Analyzing the job titles with the highest salaries.

### Salaries Based on Experience Levels

Analyzing salaries based on different experience levels.

### Histogram and Box Plot for Selected Variables

Creating visual representations for salary distribution and work year.

## Conclusion

### Summary of Findings

The analysis revealed significant trends and patterns in the salaries of data science professionals. Key findings include:

- Trends in salary growth over the years.
- The impact of experience levels on salaries.
- Job titles with the highest demand and salaries.

### Implications of the Analysis

The insights gained from this analysis can help data science professionals understand salary expectations, assist employers in making informed salary decisions, and guide educational institutions in tailoring their programs to meet industry demands.

## References

- Brownlee, J. (2020). Data Preparation for Machine Learning. Machine Learning Mastery.
- Koehler, A. (2023). Practical Data Preparation. Data Science Journal.
- Pandas Documentation. (2024). pandas.pydata.org.
