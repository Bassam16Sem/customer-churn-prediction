# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is a condition when customers stop using a service or no longer make transactions with a company. High churn rates can negatively impact company revenue and increase customer acquisition costs.

This project aims to build a machine learning model to predict customer churn based on customer demographic data, transaction history, service usage activity, and customer interaction information.

The project is developed as part of the Final Semester Project (UAS) for Bengkel Koding Data Science.

---

## 🎯 Objectives

The main objectives of this project are:

- Perform Exploratory Data Analysis (EDA)
- Build customer churn prediction models
- Compare multiple machine learning algorithms
- Evaluate model performance using classification metrics
- Optimize the best-performing model
- Deploy the final model using Streamlit Cloud

---

## 📊 Dataset Information

- Dataset Name: Sales and Marketing Customer Dataset
- Source: Kaggle
- Total Records: 15,000 rows
- Target Variable: `churn`

### Target Description

| Value | Description |
|---|---|
| 0 | Customer stays |
| 1 | Customer churns |

### Dataset Features

The dataset contains:
- Customer demographic information
- Transaction history
- User engagement metrics
- Marketing interactions
- Subscription details
- Customer satisfaction scores
- Payment methods
- Purchase behavior

Dataset Link:
https://www.kaggle.com/datasets/bhaskerpaul/sales-and-marketing-dataset

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Google Colab
- Streamlit

---

## 📁 Project Structure

```bash
customer-churn-prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── UAS-BENGKOD.ipynb
│   
│
├── src/
│   ├── preprocessing.py
│   ├── modeling.py
│   └── evaluation.py
│
├── outputs/
│   ├── figures/
│   ├── models/
│   └── reports/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📂 Folder Description

### 📁 `data/`
Folder used to store all datasets used in the project.

#### `data/raw/`
Contains original raw datasets before preprocessing.

#### `data/processed/`
Contains cleaned and processed datasets ready for modeling.

---

### 📁 `notebooks/`
Contains Google Collab files for analysis and experimentation.

#### `UAS-BENGKOD.ipynb`
Notebook for Exploratory Data Analysis (EDA), including:
- Data understanding
- Missing value analysis
- Data visualization
- Correlation analysis
- Coming Soon

---

### 📁 `src/`
Contains reusable source code modules for the project.

#### `preprocessing.py`
Functions for:
- Missing value handling
- Encoding
- Scaling
- Data cleaning

#### `modeling.py`
Functions for:
- Training machine learning models
- Saving and loading models

#### `evaluation.py`
Functions for:
- Model evaluation
- Classification metrics
- Confusion matrix visualization

---

### 📁 `outputs/`
Stores all project outputs.

#### `outputs/figures/`
Contains generated visualizations such as:
- Heatmaps
- Charts
- Confusion matrices

#### `outputs/models/`
Stores trained machine learning models in `.pkl` or `.joblib` format.

#### `outputs/reports/`
Contains experiment reports, evaluation summaries, and result files.

---

### 📄 `requirements.txt`
Contains all Python libraries and dependencies required to run the project.

---

### 📄 `README.md`
Main project documentation containing:
- Project overview
- Workflow
- Dataset information
- Model results

---

### 📄 `.gitignore`
Specifies files and folders ignored by Git during upload to GitHub, such as:
- Virtual environments
- Cache files
- Temporary files
- Large datasets

---

## 📌 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Dataset overview
- Missing value analysis
- Churn distribution analysis
- Correlation heatmap
- Feature relationship analysis

### 2. Direct Modeling

Machine learning models used:
- Logistic Regression
- Random Forest
- Voting Classifier

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 3. Preprocessing & Feature Engineering
- Missing value handling
- Encoding categorical features
- Feature scaling
- Outlier handling

### 4. Hyperparameter Tuning
- GridSearchCV
- Feature importance analysis
- Best parameter optimization

### 5. Deployment
- Streamlit web application
- Public deployment using Streamlit Cloud

---

## 📈 Initial Model Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | - | - | - | - |
| Random Forest | - | - | - | - |
| Voting Classifier | - | - | - | - |

> Model results will be updated during experimentation.

---

## 📌 Future Improvements

- Hyperparameter tuning
- Feature selection
- Model optimization
- Deployment enhancement
- Real-time prediction interface

---

## 👨‍💻 Author

**Bassam**  
Informatics Engineering Student  
Machine Learning & Data Science Enthusiast

---

## 📄 License

This project is developed for educational purposes.
