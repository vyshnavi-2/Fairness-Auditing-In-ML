
# Fairness Detection in Machine Learning

## Project Overview
Bias in machine learning models is a big deal, especially when it comes to real-world applications like hiring, lending, and law enforcement. This project focuses on **fairness detection** using the **UCI Adult Income Dataset** to ensure that our models make unbiased predictions across different demographic groups.

We tackle bias using **reweighing**, train multiple classifiers, and evaluate both accuracy and fairness metrics.

---

## Key Features
- **Preprocess** the dataset and handle missing values.
- **Apply Reweighing** to mitigate bias in training data.
- **Train models**: Logistic Regression, Random Forest, and XGBoost.
- **Evaluate performance**: Accuracy, classification reports, and confusion matrices.
- **Fairness Metrics**: Disparate Impact & Statistical Parity.
- **Visualize results** with bar plots and heatmaps.

---

## Dataset
I used the **UCI Adult Income Dataset**, which contains demographic and income-related attributes. The goal is to predict whether a person earns **more than $50K/year**.

### Attributes include:
- **Numerical**: Age, education level, hours per week, capital gain/loss, etc.
- **Categorical**: Race, sex, marital status, occupation, etc.
- **Target**: Income (>50K or <=50K)

---

##  Tech Stack
- **Python** 
- **Pandas, NumPy** (Data Processing)
- **Scikit-learn** (Machine Learning)
- **Matplotlib, Seaborn** (Data Visualization)
- **AIF360** (Fairness evaluation)

---

## Results & Fairness Metrics
- **Accuracy Comparison**: Models are evaluated based on their accuracy scores.
- **Fairness Analysis**:
  - **Disparate Impact**: Ratio of positive outcomes for unprivileged vs. privileged groups.
  - **Statistical Parity**: Difference in positive outcome rates between groups.

---

## Visualizations
 **Bar Plot for Model Accuracy**  
 **Confusion Matrix Heatmaps**  
 **Fairness Metric Comparisons**

---

