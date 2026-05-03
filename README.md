# DSA210 Project

## Identifying the Optimal Study Time for Maximum Academic Performance

## Project Objective
This project analyzes the relationship between study-related factors and academic performance. The goal is to investigate whether there is an optimal level of study behavior associated with higher exam scores.

## Dataset Description
The dataset consists of student performance records with the following variables:

- Gender, Ethnic Group  
- Parental Education Level  
- Lunch Type, Test Preparation  
- Math, Reading, and Writing Scores :contentReference[oaicite:0]{index=0}  

### Target Variable
A new variable `exam_score` is created as the average of math, reading, and writing scores.

## Methodology

### Data Preprocessing
- Missing values are handled using mode imputation  
- A new variable (`exam_score`) is created  

### Exploratory Data Analysis (EDA)
- Distribution plots are used to examine score distributions  
- Group comparisons are used to identify differences across categories  

### Hypothesis Testing
- H0: Study-related factors have no effect on exam scores  
- H1: Study-related factors significantly affect exam scores  

Statistical tests are used to evaluate these relationships.

## Analytical Approach
The analysis combines visualizations with statistical interpretation to identify meaningful relationships between variables and exam performance.

## Future Work
- Apply regression analysis  
- Explore nonlinear relationships  
- Extend the analysis with machine learning models  

## Conclusion
The project aims to determine whether academic performance can be explained and optimized based on study-related behaviors and other student characteristics.
