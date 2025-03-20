### **📌 README.md**
```markdown
# ML Regression Models: Linear, Ridge, and Lasso

## 📌 Project Overview
This repository contains my work for **Problem Set 1** of my Machine Learning course.  
The focus of this assignment is on **supervised learning, specifically regression models**, including:
- **Ordinary Least Squares (OLS) Linear Regression**
- **Ridge Regression (L2 Regularization)**
- **Lasso Regression (L1 Regularization)**  
The project explores how different regularization techniques impact model performance and how to optimize hyperparameters.

---

## 📊 Methods and Techniques
### **1️⃣ Ordinary Least Squares (OLS) Regression**
- The baseline linear regression model.
- Evaluates relationships between independent and dependent variables without any regularization.

### **2️⃣ Ridge Regression (L2 Regularization)**
- Adds an L2 penalty to reduce overfitting.
- Helps mitigate multicollinearity issues by shrinking coefficients.

### **3️⃣ Lasso Regression (L1 Regularization)**
- Uses an L1 penalty to enforce sparsity.
- Can shrink some coefficients to exactly zero, performing feature selection.

### **4️⃣ Model Evaluation Metrics**
- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**
- **Cross-Validation for Hyperparameter Tuning**

```

## 🚀 How to Run
### **1️⃣ Install Required Packages**
Make sure you have the required Python packages installed:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```

### **2️⃣ Run Jupyter Notebook**
Open and execute the notebook:
```bash
jupyter notebook regression_analysis.ipynb
```

### **3️⃣ Run Python Scripts**
To run Ridge vs. Lasso comparison:
```bash
python ridge_lasso_comparison.py
```

---

## 📈 Key Findings
- **OLS regression** provides an initial baseline but is prone to overfitting.
- **Ridge regression** (L2 penalty) helps control overfitting by reducing coefficient sizes.
- **Lasso regression** (L1 penalty) performs **feature selection** by setting some coefficients to zero.
- **Hyperparameter tuning** (via cross-validation) significantly improves model performance.
- **Trade-offs between Ridge and Lasso**:  
  - Ridge keeps all features but shrinks their influence.
  - Lasso eliminates unimportant features, making models more interpretable.

---

## 📌 Future Improvements
- **Experiment with Polynomial Regression** to capture non-linearity.
- **Implement Elastic Net** (combining L1 & L2 penalties for better regularization).
- **Compare with Tree-Based Models** like Decision Trees & Random Forest to explore nonlinear relationships.
- **Test Different Feature Selection Techniques** beyond Lasso (e.g., Recursive Feature Elimination).

