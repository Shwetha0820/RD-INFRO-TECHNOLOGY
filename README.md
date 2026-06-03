# Feature Engineering Using Python

## Internship Project - RD INFRO TECHNOLOGY

### Introduction
Feature Engineering is the process of transforming raw data into meaningful features that can improve the performance of machine learning models. In this project, categorical and numerical data were preprocessed using different feature engineering techniques.

### Objective
- Convert categorical data into numerical format.
- Create machine learning ready features.
- Scale numerical values for better analysis.

### Tools and Technologies
- Python
- Pandas
- Scikit-Learn
- Google Colab

### Dataset
The sample dataset contains employee information:

| Name | Department | Salary |
|--------|------------|---------|
| Rahul | IT | 35000 |
| Priya | HR | 45000 |
| Amit | Finance | 50000 |
| Sneha | Marketing | 41000 |
| Karan | IT | 40000 |

### Feature Engineering Techniques Used

#### Label Encoding
Converted department names into numerical values.

#### One-Hot Encoding
Created separate columns for each department category.

#### Feature Scaling
Applied StandardScaler to normalize salary values.

### Libraries Used

```python
import pandas as pd
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import StandardScaler
```

### Output
- Encoded categorical features
- One-Hot Encoded department columns
- Scaled salary values

### Learning Outcomes
- Understanding of Feature Engineering concepts
- Working with categorical and numerical data
- Using Scikit-Learn preprocessing techniques
- Preparing data for Machine Learning models

### Conclusion
This project demonstrates the implementation of Feature Engineering techniques such as Label Encoding, One-Hot Encoding, and Feature Scaling. These methods help transform raw data into a structured format suitable for machine learning applications.

### Author
Shwetha Kalagi

RD INFRO TECHNOLOGY Internship
