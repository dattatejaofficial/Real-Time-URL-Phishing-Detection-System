# Real-Time URL Phishing Detection System using Machine Learning

This project focuses on detecting phishing URLs using Machine Learning. The objective is to build a secure and intelligent system that can classify URLs as phishing (1) and legitimate (0). Phase-1 of the project includes the entire Machine Learning pipeline from **Data Prepation** to **Model Evaluation**. 

In future phases, the model will be deployed as a real-time detection service with continuous monitoring and improvement.

## Project Objectives (Phase-1)
- Clean and prepare phishing dataset
- Extract meaningful lexical features from URLs.
- Perform Exploratory Data Analysis
- Build and train multiple ML Models
- Evaluate and select the best-performing model

Deployment and monitoring will be covered in Phase-2


## Why this Project matters
Phishing attacks remain one of the most common cyber threats. Malicious links can compromise user credentials, financial information and organizational security. Detecting risky URLs instantly improve cybersecurity for users and platforms.

## Project Structure
```
phishing-detection-system/
│
├── data/
│   ├── raw/
│   └── processed/
│   └── featured/
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_data_analysis.ipynb
│   ├── 03_data_preprocessing.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_model_training.ipynb
│   ├── 06_model_evaluation.ipynb
│
├── models/
├── requirements.txt            
├── README.md                   
└── .gitignore
```

## Tools and Technologies
| Category            | Tools / Libraries                         |
|--------------------|--------------------------------------------|
| Language           | Python 3.12.10                             |
| ML & Data          | Scikit-learn, TensorFlow, Pandas, NumPy    |
| Visualization      | Matplotlib, Seaborn                        |
| Version Control    | Git & GitHub                               |
| Environment        | (venv) Virtual Environment                 |

## Dataset Information
- Feature: URL (string)
- Target: Label (1 = Phishing, 0 = Legitmate)
- Dataset source will be cited once finalized