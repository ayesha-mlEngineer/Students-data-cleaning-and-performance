# Student Performance Prediction using Machine Learning

A Machine Learning project that predicts student academic performance based on demographic, educational, and behavioral features. This notebook covers the complete data science workflow, including data preprocessing, feature engineering, model training, evaluation, and comparison of multiple regression algorithms.

## Project Overview

The objective of this project is to build and compare different Machine Learning regression models for predicting student performance.

The workflow includes:

- Data loading and exploration
- Data cleaning and preprocessing
- Handling missing values
- Standardizing inconsistent categorical values
- Outlier detection and removal
- Label Encoding
- Train-Test split
- Training multiple regression models
- Performance comparison using evaluation metrics
- Visualization of model results

---

## Project Structure

```text
.
├── BI (1).ipynb          # Main Jupyter Notebook
├── bi.csv                # Dataset (Place in the same directory)
├── README.md             # Project documentation
```

---

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Required Libraries

Install the required libraries before running the notebook.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost notebook
```

Or install from a requirements file:

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt`, create one with the following contents:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/ayesha-mlEngineer/Students-data-cleaning-and-performance.git
```

### 2. Navigate to the Project Directory

```bash
cd student-performance-prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost notebook
```

### 4. Add the Dataset

Place the dataset file:

```text
bi.csv
```

in the same directory as the notebook.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```text
BI.ipynb
```

Run all cells sequentially.

---

## Data Preprocessing

The notebook performs the following preprocessing steps:

- Handling missing values
- Cleaning inconsistent categorical values
- Standardizing gender labels
- Standardizing country names
- Standardizing residence names
- Standardizing previous education labels
- Removing outliers using the IQR method
- Label encoding categorical features

---

## Machine Learning Models

The following regression models are implemented:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- XGBoost Regressor

---

## Model Performance

| Model | Score |
|--------|------:|
| Linear Regression | 75.05 |
| Gradient Boosting | 73.78 |
| Random Forest | 72.61 |
| XGBoost | 58.19 |
| Support Vector Regressor (SVR) | 48.22 |

Linear Regression achieved the best performance on this dataset.

---

## Visualizations

The project includes visualizations such as:

- Boxplots for outlier detection
- Model performance comparison using bar charts
- Dataset exploration plots

---

## Features Used

Examples of input features include:

- Age
- Gender
- Country
- Residence
- Previous Education
- Entry Exam Score
- Study Hours
- Database (DB) Score
- Python Score

*The exact features depend on the dataset.*

---
