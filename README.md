# DSA210 Project  
## Identifying the Optimal Study Time for Maximum Academic Performance  

## Project Objective  
This project investigates how different study-related factors affect students’ academic performance.  
The main goal is to determine whether certain behaviors—such as study time and test preparation—are associated with higher exam scores.

---

## Dataset Description  
The dataset contains student-level observations including:

- Gender, Ethnic Group  
- Parental Education Level  
- Lunch Type  
- Test Preparation Course  
- Weekly Study Hours  
- Math, Reading, and Writing Scores  

### Target Variable  
A new variable **`ExamScore`** is created as the average of Math, Reading, and Writing scores.

---

## Methodology  

### Data Preprocessing  
- Missing values were handled using **mode imputation**  
- A new feature (**ExamScore**) was engineered  

---

### Exploratory Data Analysis (EDA)  
- Countplots and grouped averages were used to understand distributions  
- Relationships between categorical variables and scores were visually explored  

---

### Hypothesis Testing  

#### 1. Effect of Test Preparation  
- **Test used:** Independent t-test  
- **Result:**  
  - T-statistic ≈ 39.10  
  - P-value ≈ 0.0  

 Students who completed the test preparation course have **significantly higher exam scores**.

---

#### 2. Effect of Weekly Study Hours  
- **Test used:** One-way ANOVA  
- **Result:**  
  - F-statistic ≈ 75.65  
  - P-value ≈ 1.67e-33  

 There is a **statistically significant difference** between study hour groups.

---

## Key Findings  

- Test preparation has a **strong positive impact** on performance  
- Students who study more tend to have **higher average scores**  
- Weekly study hours and preparation are the **most influential factors**  
- Other variables (gender, parental education, etc.) show **weaker effects**

---

## Final Conclusion  

This analysis demonstrates that **student effort and preparation play a crucial role in academic success**.  

Among all variables, **test preparation and study time** show the strongest relationship with exam performance.  

Students who both **prepare for exams and dedicate more time to studying** consistently achieve higher scores.

---

## Key Insight  

> Academic success is less about background factors and more about consistent effort and preparation.
