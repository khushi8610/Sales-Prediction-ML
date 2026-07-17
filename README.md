# 📈 Sales-Prediction-ML


## 📌 Project Overview

This project demonstrates how machine learning can be used to predict product sales based on advertising expenditure across different media channels. Using the classic **Advertising.csv** dataset, regression models are developed to analyze the relationship between advertising budgets and sales performance.

The project covers the complete machine learning workflow, including data exploration, visualization, model training, evaluation, residual analysis, and feature importance analysis.

---

## 🎯 Objectives

- Analyze the relationship between advertising expenditure and product sales.
- Perform Exploratory Data Analysis (EDA) to understand the dataset.
- Build a Linear Regression model as the baseline.
- Train and compare a Random Forest Regressor.
- Evaluate model performance using standard regression metrics.
- Identify the advertising channel with the greatest impact on sales.

---

## 📂 Dataset

**Dataset:** Advertising.csv

The dataset contains **200 observations** with the following variables:

| Feature | Description |
|---------|-------------|
| TV | Advertising budget spent on television (in thousands of dollars) |
| Radio | Advertising budget spent on radio (in thousands of dollars) |
| Newspaper | Advertising budget spent on newspapers (in thousands of dollars) |
| Sales | Product sales (in thousands of units) |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value analysis
- Descriptive statistics
- Pairplot visualization
- Scatter plots
- Correlation matrix heatmap

---

## 🤖 Machine Learning Models

### 1. Linear Regression

Used as the baseline regression model to establish the relationship between advertising expenditure and sales.

### 2. Random Forest Regressor

An ensemble learning algorithm that captures more complex relationships and provides feature importance scores.

---

## 📈 Model Evaluation Metrics

Both models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model was selected based on these evaluation metrics.

---

## 📉 Residual Analysis

Residual analysis was performed to evaluate prediction errors.

A well-performing regression model should produce residuals that are randomly distributed around zero, indicating that the model captures the relationship between advertising expenditure and sales effectively.

---

## 📌 Feature Importance

Feature importance analysis was conducted using model coefficients and feature importance scores to determine which advertising channel contributes most to sales prediction.

---

## 📁 Project Structure

```
Sales-Prediction-ML
│
├── Sales_Prediction.ipynb
├── Advertising.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Sales-Prediction-Using-Python.git
```

### 2. Navigate to the project folder

```bash
cd Sales-Prediction-Using-Python
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
Sales_Prediction.ipynb
```

Run all cells sequentially to reproduce the analysis and model results.

---

## 📷 Sample Visualizations

The notebook includes:

- Pairplot
- Sales vs TV Scatter Plot
- Sales vs Radio Scatter Plot
- Sales vs Newspaper Scatter Plot
- Correlation Heatmap
- Actual vs Predicted Sales Plot
- Residual Plot
- Feature Importance Bar Chart

---

## 📌 Key Insights

- Advertising expenditure has a measurable impact on product sales.
- TV advertising generally shows the strongest relationship with sales.
- Radio advertising also contributes positively to sales prediction.
- Newspaper advertising has comparatively lower influence.
- Comparing multiple regression models provides a better understanding of prediction performance.

---

## 🔮 Future Improvements

- Apply Polynomial Regression for non-linear relationships.
- Perform hyperparameter tuning to improve model performance.
- Train additional ensemble models such as XGBoost or Gradient Boosting.
- Deploy the model using Streamlit or Flask.
- Use larger and more diverse advertising datasets for improved generalization.

---

## 📚 Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 👩‍💻 Author

**Khushi Kapoor**

B.Tech Computer Science Engineering

Aspiring Data Analyst | Data Science Enthusiast | Java Developer

---

## ⭐ If you found this project helpful, consider giving it a star!
