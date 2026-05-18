# DSA210 Project  
## Identifying the Optimal Study Time for Maximum Academic Performance  

**Melda Arık — 34268**  

---

## Project Overview  

This project examines how different study-related factors affect students’ academic performance.  

The main focus is understanding whether variables such as weekly study hours and test preparation are associated with higher exam scores and whether these variables can be used to predict academic performance.

The project includes:
- Exploratory Data Analysis (EDA)
- Hypothesis Testing
- Machine Learning Models

---

## Research Question  

> How do study habits and preparation affect students’ exam performance?

---

## Dataset  

The project uses the **Student Test Scores: Extended Dataset** from Kaggle.  

The dataset includes variables such as:
- Gender
- Parent Education
- Lunch Type
- Test Preparation
- Weekly Study Hours
- Number of Siblings
- Transportation Method
- Math, Reading, and Writing Scores

### Target Variable  

A new variable called `ExamScore` was created as the average of:
- Math Score
- Reading Score
- Writing Score

---

## Methods  

### Data Preprocessing  
- Missing values were handled using mode imputation  
- A new feature (`ExamScore`) was created  

### Exploratory Data Analysis  
- Distribution analysis  
- Group comparisons  
- Countplots and visual analysis  

### Hypothesis Testing  
- Independent t-test  
- One-Way ANOVA  

### Machine Learning  
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

Models were evaluated using:
- RMSE
- R² Score
- Cross-validation

---

## Main Findings  

- Students who study more generally achieve higher exam scores  
- Test preparation is associated with better academic performance  
- Weekly study hours showed statistically significant differences between groups  
- Linear Regression performed better than the other tested models  
- Machine learning models showed limited predictive performance overall  

One important finding of the project is that statistically significant variables may still have limited predictive power in machine learning models.

---

## Final Note  

This project combines statistical analysis and machine learning methods to better understand the relationship between study habits and academic performance.  

The findings suggest that study-related variables are important, but they are not sufficient alone to fully explain student success.
