
#  Wine Quality Prediction (Regression) – Hackathon Project

##  Overview
This project predicts the **quality of red wine** using physicochemical properties through a **Linear Regression** model.  
It was developed as part of a machine learning hackathon focused on EDA, model building, evaluation, and feature interpretation.

---

##  Dataset
**Red Wine Quality Dataset**  
Sources:  
- UCI Machine Learning Repository  
- Kaggle (Wine Quality Dataset - Red/White)

The dataset includes chemical features such as acidity, chlorides, density, sulphates, alcohol, and more.

---

##  Objectives
The main goals of the hackathon were:

1. Load dataset, check shape, and validate missing values  
2. Split data into features **X** and target **y (quality)**  
3. Train a **baseline Linear Regression model**  
4. Report **RMSE** and **R² score** on the test set  
5. Identify top 3 features with highest absolute coefficients  
6. Write a short report on findings, metrics, and model justification  

---

##  Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

##  Exploratory Data Analysis (EDA)
Key insights from EDA:

- **Alcohol** has one of the strongest positive correlations with wine quality  
- **Volatile acidity** negatively impacts wine quality  
- **Density** and **residual sugar** show moderate relationships  
- The target variable *quality* is slightly imbalanced around classes 5–7  

---

##  Model Used: Linear Regression
A simple and interpretable **Linear Regression** model was selected as a baseline.

### 🔧 Preprocessing steps:
- StandardScaler applied on numerical features  
- Categorical encoding (if applicable)  
- Train-test split (80% train, 20% test)

---

##  Model Performance

| Metric | Value |
|--------|--------|
| **RMSE** | **0.6870** |
| **R² Score** | **0.3396** |

### Interpretation:
- RMSE of **0.6870** indicates the average error in predicting wine quality  
- R² of **0.3396** means the model explains ~34% of the variance  
- Reasonable for a baseline model given the noise and subjectivity of wine scoring  

---

##  Top 3 Most Influential Features
Based on absolute coefficient values:

1. **Residual sugar — positive effect**  
2. **Density — negative effect**  
3. **Alcohol — positive effect**

These features played the biggest role in determining predicted wine quality.

---

##  Final Report Summary
The Linear Regression model provides a strong baseline and highlights key chemical properties influencing wine quality.  
While the predictive performance is moderate, the model is interpretable and meets all hackathon requirements.

Future work may include:
- Ridge/Lasso Regression  
- Random Forest or Gradient Boosting  
- Hyperparameter tuning  
- Non-linear feature engineering  

---

##  Project Structure

```
 wine-quality-regression
│
├── winequality-red-regression.ipynb   # Main Notebook
├── README.md                           # Project Documentation
└── winequality-red.csv                 # Dataset (optional)
```

---

##  Author
**Varshini**  
MCA Student – Manipal Institute of Technology  
Skills: Python, Machine Learning, Data Analysis, Web Development  

---

# 🙌 Thank You!
