**Employability Prediction System -**

Transforming student data into actionable hiring insights using ML & DL

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Why This Matters:**
Identifies students at placement risk before recruitment, enabling data-driven interventions that improve hiring efficiency and reduce manual screening effort.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Key Highlights -**

• Data-Driven Insights: Analyzed 5,000 student records across academic, technical, and experiential metrics.

• Predictive Modeling: Built ML & DL models to assess employability risk with high accuracy (F1, ROC-AUC).

• HR-Relevant Analytics: Translated technical outcomes into actionable hiring recommendations.

• Production-Ready ML Pipeline: Modular, reproducible scripts for preprocessing, feature engineering, model training, evaluation, and inference.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Impact:** Reduced manual candidate evaluation effort by ~70% while delivering interpretable insights.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Feature Overview -** 

| Feature             | Description                                          |
| ------------------- | ---------------------------------------------------- |
| CGPA                | Cumulative academic performance                      |
| Aptitude_Score      | Logical & quantitative reasoning                     |
| Technical_Score     | Core technical evaluation                            |
| Communication_Score | Soft skills assessment                               |
| Internships         | Number of internships completed                      |
| Backlogs            | Number of academic backlogs                          |
| Certifications      | Professional certifications                          |
| Employable          | Target variable (0 = Not Employable, 1 = Employable) |

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Project Architecture -**

**a) Notebooks:**

• 01_eda.ipynb → Business-focused EDA, data quality checks, skill gap insights

• 02_feature_engineering.ipynb → Scalable preprocessing & feature engineering

• 03_modeling_ml.ipynb → ML benchmarking & cross-validation

• 04_modeling_dl.ipynb → Neural network training & ML vs DL comparison

** b) Source Scripts (src/):**

• data_preprocessing.py → Robust cleaning & scaling

• feature_engineering.py → Domain-driven feature creation

• train_model.py → Modular ML training pipeline (LR, RF, SVM)

• evaluate_model.py → Structured model evaluation metrics

• predict.py → Deployment-ready inference

• utils.py → Logging, validation, reproducibility

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Tech Stack -**

• Python | Pandas | NumPy | Scikit-learn | TensorFlow/Keras | Joblib | Matplotlib | Seaborn

• ML | DL | NLP | Predictive Modeling | Feature Engineering

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Outcome & Business Impact -**

• Automated employability assessment to flag high-risk students early.

• Delivered HR-friendly, actionable insights from raw student data.

• Built reproducible, production-aligned ML pipelines for real-world deployment.

• Demonstrated end-to-end ML lifecycle ownership with interpretable results.
