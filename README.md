# 🚗 AlphaCare Insurance Analytics Project

This project focuses on risk analysis and predictive modeling using historical health insurance data to simulate auto-insurance marketing strategies.

## 📌 Objectives

- Perform Exploratory Data Analysis (EDA)
- Test hypotheses related to customer risk segments
- Build predictive models to estimate insurance charges (proxy for risk)
- Make business recommendations based on data

## 📊 Dataset

We use a dataset with the following features:

| Column     | Description                |
|------------|----------------------------|
| age        | Age of the individual      |
| sex        | Gender (male/female)       |
| bmi        | Body mass index            |
| children   | Number of children         |
| smoker     | Smoker status              |
| region     | Geographic region          |
| charges    | Insurance charges (target) |

## 🧪 Task Breakdown

| Task | Description |
|------|-------------|
| Task 1 | EDA, initial setup, GitHub CI |
| Task 2 | DVC version control (TBD) |
| Task 3 | Hypothesis testing (smoker, gender, region) |
| Task 4 | Predictive modeling using Linear Regression |

## ⚙️ Tech Stack

- Python (Pandas, Seaborn, Scikit-learn)
- Jupyter Notebooks
- Git & GitHub
- GitHub Actions (CI)
- DVC (Coming in Task 2)

## ✅ How to Run

1. Clone the repo  
2. Install dependencies  
```bash
pip install -r requirements.txt
