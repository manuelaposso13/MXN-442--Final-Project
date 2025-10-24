# Customer Churn Prediction in the Telecommunication Industry  
### Using Machine Learning and GenAI-Driven Optimisation

---

##  Overview  
This project replicates and extends the study by **Nguyen, Tran, & Dao (2022)** on predicting customer churn in the telecommunications industry using **Support Vector Machines (SVMs)**.  
The goal is to identify customers at risk of leaving by comparing and optimising multiple models, focusing on **recall** — the most important metric for business retention decisions.

The project evaluates and improves several models:
- **Logistic Regression** (baseline interpretability)
- **Decision Tree** (non-linear interpretability)
- **Random Forest** (ensemble learning)
- - **Neural Network**
- **Baseline comparison: SVM (Nguyen et al., 2022)**

Further refinements included:
- **Hyperparameter tuning** via `GridSearchCV`  
- **Feature selection** (forward selection)  
- **Nested Cross-Validation** for unbiased evaluation  
- **Regularisation via pruning**  
- **SMOTE** for class rebalancing  
- **GenAI guidance** (ChatGPT-5) for workflow optimisation and implementation feedback  

---

##  Objective  
To identify a **reliable and interpretable churn prediction model** that maximises **recall**, ensuring customers likely to churn are accurately identified, even at the cost of minor precision or accuracy trade-offs.

---

##  Repository Contents  

| File / Folder | Description |
|:--|:--|
| `MXN_442_Assignment2.ipynb` | Main Jupyter Notebook with full code, analysis, and visualisations. |
| `MXN_442_Assignment2_Code.pdf` | PDF printout of the Jupyter Notebook (for submission). |
| `churn80.csv` | Training dataset containing 80% of original data. |
| `churn20.csv` | Validation dataset containing 20% of original data. |
| `telecom_churn_final.csv` | Cleaned and preprocessed dataset used for model training and testing. |
| `README.md` | Project documentation (this file). |
| `references.txt` | Bibliographic references in APA 7 style. |

---

## ⚙️ Requirements  

Install required libraries before running the notebook:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn ISLP


## Author

Manuela Posso Baena
Master of Data Analytics, Queensland University of Technology (QUT)


🏛️ Academic Context

This project was completed as part of the assessment for MXN442 — Modern Statistical Computing Techniques
Queensland University of Technology (QUT), Semester 2, 2025, Octuber 24th 2025

© 2025 — All rights reserved.
Reproduction or distribution without permission is prohibited.


