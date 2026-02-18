**Employability Prediction – ML Core (src)**

Structured machine learning pipeline to predict student placement outcomes using academic, practical, and behavioral indicators.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

**Architecture -**

src/
├── data_preprocessing.py # Cleaning + scaling + encoding pipeline
├── feature_engineering.py # Domain-driven composite features
├── train_model.py # Model training + comparison (LR, RF, SVM)
├── evaluate_model.py # Structured metrics + confusion matrix
├── predict.py # Deployment-ready inference
└── utils.py # Logging, validation, reproducibility

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**What This Signals -**

• End-to-end ML lifecycle separation  

• Feature engineering aligned with hiring logic 

•  F1-based model selection  

• Stratified split + reproducibility  

• Saved model artifacts (`best_model.pkl`) 

• Inference separated from training 

• Production-oriented modular design  

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Tech Stack -**

• Python 

• Pandas 

• Scikit-learn 

• Joblib 

• Modular ML Architecture

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Business Focus -**

• Predict `PlacementStatus` using CGPA, Internships, Projects, Certifications, Aptitude Score, Soft Skills, Extracurriculars, and Demographics.

• Designed to reflect real-world ML system structure — not notebook-only experimentation.
