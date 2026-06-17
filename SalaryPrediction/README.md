# Salary Prediction with Linear Regression

This project predicts salaries based on job features using **Linear Regression (Normal Equation)**.

---

## Dataset
- **Source:** Job Salary Prediction Dataset  
- **Rows:** 250,000  
- **Features:** job title, experience, education, skills, industry, company size, location, remote work, certifications  
- **Target:** salary  

---

## Steps
1. Load dataset with Pandas.  
2. Encode categorical features (education, industry, company size, etc.).  
3. Build feature matrix `X` and target `Y`.  
4. Apply Normal Equation to calculate parameters `θ`.  
5. Predict salaries and measure error (MAE).  

---

## Results
- **Mean Absolute Error (MAE):** ~26,590  
- **Average Salary in Dataset:** ~145,718  

---

## How to Run
1. Clone repo:
   ```bash
   git clone https://github.com/saivivekreddydevaram/ML-MINI-PROJECTS.git
