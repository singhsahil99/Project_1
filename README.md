# ICU Mortality Prediction 🏥

This project builds a machine learning pipeline to predict **ICU patient mortality** using demographic, severity, and physiological data from day 3 of admission.  
Developed as part of my **M.Sc. Data Science & Engineering** coursework at **Politecnico di Torino**.

---

## 📌 Overview

- **Goal:** Predict ICU patient survival based on clinical and physiological data  
- **Dataset:** ~9,100 patient records from five U.S. medical centers  
- **Features:** Demographics, vitals, lab results, disease class, DNR status, comorbidities, ADL indices  
- **Approach:** Data cleaning → feature scaling & encoding → PCA → model training & comparison  

---

## 🛠 Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter  
- **Tools:** VS Code, Jupyter Notebook

---

## 🧠 Methodology

1. **Preprocessing**
   - Removed duplicates & handled missing values (median/mode)
   - One-hot encoded categorical variables
   - Min–max scaled numerical features
   - Applied **PCA** for dimensionality reduction

2. **Model Training**
   - Trained & tuned SVM, Random Forest, KNN, and Decision Tree
   - Used cross-validation for hyperparameter optimization

3. **Evaluation**
   - Metrics: F1-score, Precision, Recall
   - Compared train vs. evaluation performance

---

## 📊 Results

| Model           | Train F1 | Eval F1 |
|-----------------|---------|--------|
| **SVM**         | ~0.841 | ~0.747 ✅ |
| Random Forest   | ~0.833 | ~0.740 |
| KNN             | ~0.826 | ~0.704 |
| Decision Tree   | ~0.810 | ~0.685 |

✅ **SVM achieved the best generalization performance** with the highest F1 score.

---

## 🏁 Conclusion

This project demonstrates that **machine learning can meaningfully predict ICU patient mortality** when data is properly preprocessed and reduced using PCA.  
**SVM outperformed all other models** (F1 ≈ 0.747) and is the most reliable choice for this task.  
Future improvements may include exploring ensemble models (XGBoost, LightGBM) and deploying the solution as an API for real-time hospital use.

---

## 🚀 How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/singhsahil99/Project_1.git
   cd Project_1


## 📂 Repository Structure
Project_1/
├─ notebooks/
│   └─ s331649_DSLPROJECT.ipynb
├─ requirements.txt
├─ README.md
└─ .gitignore



## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/singhsahil99/Project_1.git
   cd Project_1


