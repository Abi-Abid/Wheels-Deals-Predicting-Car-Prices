# Wheels & Deals: Predicting Car Prices

## Overview
This project explores **used car pricing** through **data analysis and machine learning** to identify key factors influencing car prices. The workflow includes data preprocessing, exploratory data analysis (EDA), and model development using Python.

## Dataset
- The dataset contains information on used car listings, including attributes like **brand, model, year, mileage, fuel type, transmission**, and **price**, total 27 attributes.
- The source of the dataset is IBM Data Science Professional Certification by Coursera.

## Project Workflow
This project is divided into five key stages:

### 1️⃣ Importing & Exporting Data
- Load the dataset into a Pandas DataFrame.
- Handle different file formats (CSV, JSON, etc.).
- Export cleaned data for further processing.

### 2️⃣ Data Wrangling
- Handle missing values and outliers.
- Convert data types and standardize column names.
- Feature engineering (creating new variables for better insights).

### 3️⃣ Exploratory Data Analysis (EDA)
- Statistical summaries of numerical and categorical features.
- Data visualization using **Matplotlib & Seaborn**.
- Identifying correlations between variables.

### 4️⃣ Model Development
- Selecting input features and target variable.
- Applying **Simple Linear Regression, Multiple Linear Regression and Polynomial Regression** to predict car prices.
- Splitting data into training and testing sets.

### 5️⃣ Model Evaluation & Refinement
- Evaluating model performance using **metrics like RMSE, MAE, and R²**.
- Fine-tuning hyperparameters for improved accuracy.
- Comparing different models and selecting the best one.

## Technologies Used
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebook**
- **Machine Learning** (Simple Linear Regression, Multiple Linear Regression, Polynomial Regression)

## Key Insights & Findings
- **Fuel type, mileage, and year** significantly impact used car prices.
- Outlier detection revealed **unrealistic price values**, which were cleaned during data wrangling.
- Linear Regression provided a **baseline model**, but more complex models may yield better accuracy.
- Comparing these three models, we conclude that "MLR model is the best model" to be able to predict price from our dataset. This result makes sense since we have 27 variables in total and we know that one of those variables are potential predictors of the final car price.

## Future Improvements
- Implement **advanced machine learning models** (Random Forest, XGBoost).
- Include more features like **car condition and location-based pricing**.
- Deploy the model as a **web app** using Flask or Streamlit.

---
## Author
**Dudekula Abid Hussain**

Email iD - dabidhussain2502@gmail.com

