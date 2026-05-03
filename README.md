# Employee Performance Index Prediction
### End-to-End Data Science Project | INX Future Inc.


## Problem Statement

INX Future Inc., a leading data analytics and automation solutions provider, has seen declining employee performance indexes in recent years. The CEO initiated this data science project to:

- Identify the **core underlying causes** of performance issues
- Build an ML model to **predict employee performance rating**
- Find **top 3 factors** affecting performance
- Give **actionable HR recommendations**

---

## Dataset

| Property | Details |
|---|---|
| **Source** | Kaggle — INX Future Inc. Employee Performance |
| **Link** | https://www.kaggle.com/datasets/eshwarganta/employee-performance-analysis-inx-future-inc |
| **Records** | 1,200 employees |
| **Features** | 28 attributes |
| **Target** | PerformanceRating (1=Low, 2=Good, 3=Excellent, 4=Outstanding) |

### Key Features Include:
- Demographics: Age, Gender, Marital Status, Education
- Job Info: Department, Job Role, Job Level, Business Travel
- Satisfaction Metrics: Environment, Job, Relationship, Work-Life Balance
- Performance Indicators: Salary Hike %, Training Times, Overtime
- Tenure Info: Years at Company, Years in Role, Years Since Promotion

---

## Project Workflow

```
1. Problem Definition
2. Data Collection / Dataset Selection
3. Data Cleaning & Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Model Building (5 ML Algorithms)
7. Model Evaluation & Hyperparameter Tuning
8. Visualization of Results
9. Conclusion & Recommendations
```

---

## Models Used

| Model | Test Accuracy |
|---|---|
| Logistic Regression | ~72% |
| Decision Tree | ~79% |
| **Random Forest** | **~93%** |
| Gradient Boosting | ~91% |
| Support Vector Machine | ~85% |

**Best Model: Random Forest (with GridSearchCV tuning)**

---

## Key Findings

### Top 3 Factors Affecting Performance:
1. **EmpLastSalaryHikePercent** — Salary growth is the strongest predictor
2. **EmpEnvironmentSatisfaction** — Workplace environment drives performance
3. **EmpWorkLifeBalance** — Work-life balance significantly impacts output

### Department Insights:
- Data Science and Development departments show highest avg performance
- Sales department shows highest variability in performance ratings

---

## Business Recommendations

1. **Increase salary hikes** for high-performing employees to retain talent
2. **Improve work environment** — better facilities, flexible work options
3. **Promote work-life balance** — hybrid policies, manage overtime
4. **Regular promotion cycles** — reduce stagnation and disengagement
5. **Rotate managers** — refresh team dynamics periodically

---

## Project Structure

```
Employee-Performance-Index/
|
|-- Employee_Performance_Index.ipynb   # Main Jupyter Notebook
|-- README.md                          # This file
|-- requirements.txt                   # Python dependencies
|-- data/
|   |-- INX_Future_Inc_Employee_Performance.csv  # Dataset
|-- images/
|   |-- target_distribution.png
|   |-- department_performance.png
|   |-- key_features.png
|   |-- correlation_heatmap.png
|   |-- confusion_matrix.png
|   |-- model_comparison.png
|   |-- feature_importance.png
```

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook Employee_Performance_Index.ipynb
```

---

## Requirements

```
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
scikit-learn>=1.2.0
jupyter>=1.0.0
nbformat>=5.7.0
```

---

## Submission Info

| Item | Details |
|---|---|
| **Course** | Data Science |
| **Student** | [Your Name] |
| **Dataset** | INX Future Inc. Employee Performance |
| **Assigned** | Week 7 |
| **Deadline** | End of Week 8 |
| **Presentation** | Week 8 Demo Day |


*Made with Python | Scikit-Learn | Pandas | Matplotlib | Seaborn*
