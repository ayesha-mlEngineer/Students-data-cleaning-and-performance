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
git clone https://github.com/your-username/student-performance-prediction.git
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
BI (1).ipynb
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

## Learning Outcomes

This project demonstrates:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Handling Missing Data
- Outlier Detection
- Encoding Categorical Variables
- Machine Learning Regression
- Model Evaluation
- Data Visualization

---

## Notes

- Ensure that `bi.csv` is located in the same folder as the notebook.
- Run the notebook cells in order to avoid dependency issues.
- Some preprocessing steps may require adjustments depending on the dataset version.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature selection
- Machine Learning pipelines
- Model serialization using Pickle or Joblib
- Deployment using Flask, FastAPI, or Streamlit

---

## Author

**Your Name**

GitHub: https://github.com/your-username

---

## License

This project is intended for educational and learning purposes.
