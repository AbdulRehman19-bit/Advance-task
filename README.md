# Advance-task
# Loan Default Risk with Business Cost Optimization

##  Objective
Predict the likelihood of a loan default and optimize decision-making based on business costs associated with false positives and false negatives.

##  Dataset
**Dataset Name**: Synthetic or real Home Credit Default Risk Dataset  
**Note**: If original dataset isn't available, synthetic data is used for demonstration.  
If using the real one, upload `application_train.csv` from [Home Credit Dataset on Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data).

##  Steps Covered

### 1. Data Cleaning & Preprocessing
- Generated synthetic data with binary target (loan default).
- Checked and removed null values.
- Split into train/test sets.

### 2. Modeling
- Trained **Logistic Regression** model (you can also try Random Forest, XGBoost).
- Used `StandardScaler` for normalization.

### 3. Business Cost Optimization
- Defined cost:
  - False Positive = \$500
  - False Negative = \$1000
- Found the best decision threshold that minimizes total business cost.

### 4. Evaluation Metrics
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC-AUC
- Cost curve vs threshold plot

### 5. Visualizations
- ROC Curve
- Cost Optimization Curve
- Final Confusion Matrix

##  Insights & Conclusion
- Optimized threshold: `~0.38`
- Model performance balanced to minimize financial loss
- Business-aware metrics can improve ROI over traditional metrics

---

##  Technologies Used
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## Skills Gained
- Cost-sensitive binary classification  
- Threshold tuning for risk optimization  
- Confusion matrix and business-driven evaluation  
- Model interpretability and KPI alignment

---

##  How to Run
1. Clone this repo
2. Open `Advance tasks.ipynb` in Jupyter or VSCode
3. Run all cells

---

## 🔗 Submission
Uploaded as part of Data Science & AI/ML Internship at DevelopersHub Corporation  
Task: **Loan Default Risk with Business Cost Optimization**  
Submission Date: **[Your Date]**

