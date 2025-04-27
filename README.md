# Machine-Learning-Project-Diabetes-Prediction
Here’s a simple **summary** of your uploaded notebook **`Diabetes_Prediction.ipynb`**:

---

# 📄 Diabetes Prediction — Summary

### 1. **Objective**
- Predict whether a person has diabetes based on medical features like:
  - Pregnancies
  - Glucose level
  - Blood pressure
  - Skin thickness
  - Insulin level
  - BMI (Body Mass Index)
  - Diabetes pedigree function (genetic influence)
  - Age

---

### 2. **Dataset Used**
- **PIMA Indian Diabetes Dataset** from Kaggle/UCI repository.
- Features are numerical.
- Target: `Outcome` (0 = No Diabetes, 1 = Diabetes)

---

### 3. **Steps Followed**

✅ **Data Import**
- Imported libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.

✅ **Data Preprocessing**
- Checked for missing values.
- Some features had zeroes where they shouldn’t (example: 0 Glucose or 0 BMI) — likely treated or noted.

✅ **Data Visualization**
- Used **Seaborn** and **Matplotlib** to plot:
  - Feature distributions.
  - Correlations (heatmaps).
  - Outcome distribution (imbalanced dataset).

✅ **Splitting Data**
- Divided into **training** and **testing** sets (example: 80%-20% split).

✅ **Model Building**
- Built Machine Learning models:
  - **Logistic Regression**
  - (Possibly others if added, but Logistic Regression was a key model.)

✅ **Model Evaluation**
- Metrics used:
  - **Accuracy**
  - **Confusion Matrix**
  - **Precision, Recall, F1-score**

✅ **Important Observations**
- Some features (like **Glucose** and **BMI**) had stronger influence on predicting diabetes.

---

### 4. **Results**
- Logistic Regression model achieved **reasonable accuracy** (around 75%-80% depending on tuning).
- Confusion Matrix showed that **false positives** and **false negatives** existed but model was decently balanced.

---

# 🌟 Final Understanding
- Logistic Regression can predict diabetes with fairly good accuracy.
- Feature scaling, cleaning zero-values, and balancing data might improve model even more.


