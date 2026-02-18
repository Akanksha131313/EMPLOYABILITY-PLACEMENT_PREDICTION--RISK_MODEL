**Data Overview -**

• Dataset Name: employability_prediction_data.csv

• Records: 5,000

• Features: 8

• Target Variable: Employable (Binary: 0 = Not Employable, 1 = Employable)

---------------------------------------------------------------------------------------------------------------------------------------------------------------

**Business Context -**

• This dataset is designed to model early employability risk among students based on academic performance, technical capability, and experiential indicators.

• The objective is to identify students at placement risk before the recruitment cycle, enabling proactive intervention strategies.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Feature Description -**

| Feature             | Description                                          |
| ------------------- | ---------------------------------------------------- |
| CGPA                | Cumulative academic performance                      |
| Aptitude_Score      | Quantitative and logical reasoning assessment score  |
| Technical_Score     | Core technical evaluation score                      |
| Communication_Score | Communication and soft skill assessment              |
| Internships         | Number of completed internships                      |
| Backlogs            | Number of academic backlogs                          |
| Certifications      | Professional certifications completed                |
| Employable          | Target variable (0 = Not Employable, 1 = Employable) |

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Data Source -**

• Synthetic dataset generated for modeling and experimentation purposes.

• Designed to simulate realistic campus placement evaluation metrics.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Data Loading -**

import pandas as pd

df = pd.read_csv("../data/cleaned/employability_prediction_data.csv")
df.head()

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Data Characteristics -**

• Structured tabular dataset

• Binary classification target

• Mix of continuous and discrete variables

• Suitable for ML and DL experimentation

• No missing values (pre-cleaned dataset)
