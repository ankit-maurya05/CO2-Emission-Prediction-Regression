# 🚗 Car CO2 Emissions Regression

Exploratory data analysis and CO2 emissions prediction on a car dataset using Linear, Ridge, and Lasso regression models.

---

## 📌 Overview

This project analyzes a dataset of vehicles to understand the factors that influence CO2 emissions. It includes data cleaning, exploratory data analysis (EDA), feature engineering, and a comparison of three regression models to predict CO2 emissions (g/km).

---

## 📂 Dataset

**File:** `car_dataset.csv`

The dataset contains information about vehicles including:

| Feature | Description |
|---|---|
| Model year | Year of the vehicle |
| Make / Model | Manufacturer and model name |
| Vehicle class | Category (e.g., SUV, Full-size) |
| Engine size (L) | Engine displacement in litres |
| Cylinders | Number of cylinders |
| Transmission | Transmission type |
| Fuel type | Type of fuel used |
| City / Highway / Combined (L/100 km) | Fuel consumption metrics |
| Combined (mpg) | Fuel efficiency in miles per gallon |
| CO2 emissions (g/km) | **Target variable** |
| CO2 rating / Smog rating | Environmental ratings |

---

## 🔍 Project Workflow

1. **Data Loading & Cleaning** — Importing the dataset and handling missing/inconsistent values
2. **Exploratory Data Analysis (EDA)** — Visualizing distributions, correlations, and trends using Matplotlib and Seaborn
3. **Feature Engineering** — Encoding categorical variables and scaling features
4. **Model Training & Evaluation** — Training and comparing three regression models:
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
5. **Residual Analysis** — Checking model assumptions via residual plots

---

## 📊 Results

| Model | R² Score |
|---|---|
| Linear Regression | 0.9956 |
| Ridge Regression | 0.9956 |
| Lasso Regression | 0.9949 |

All three models achieve very high R² scores, with Linear and Ridge regression performing nearly identically.

---

## 🛠️ Tech Stack

- Python 3.12
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-co2-emissions-regression.git
   cd car-co2-emissions-regression
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Add the `car_dataset.csv` file to the project directory.

4. Open the notebook:
   ```bash
   jupyter notebook car_co2_regression_analysis.ipynb
   ```

