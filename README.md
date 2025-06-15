# 🛍️ Customer Lifetime Value Prediction

This project aims to **predict Customer Lifetime Value (CLV)** using historical transaction data from an online retail business. It leverages **data analytics** and **machine learning** to extract valuable business insights and provide predictive power for future customer behavior. The analysis leverages a comprehensive online retail dataset and employs robust data cleaning, exploratory data analysis (EDA), and predictive modeling to deliver actionable business insights.

---

## 📌 Project Overview

- **Objective**: Predict CLV using historical transaction data from an online retailer.
- **Key Techniques**:
  - Data Cleaning & Preprocessing
  - Feature Engineering
  - Exploratory Data Analysis (EDA)
  - Regression Modeling: Linear Regression, Random Forest Regressor
  - Model Evaluation using RMSE and R²

---

## 🛠️ Tools & Libraries

- **Language**: Python
- **Libraries**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
- **Platform**: Google Colab / Jupyter Notebook

---

## 📂 Dataset Information

- **Source**: [Kaggle - Online Retail Dataset]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset))
- **Note**: For this project, the dataset was uploaded to Google Drive. You’ll need to update the dataset path if using a different location.

---

## 📁 Project Structure

### 1. Data Loading & Cleaning
- Load dataset from Google Drive
- Remove entries with missing `CustomerID`
- Filter out negative or zero `Quantity` and `UnitPrice`
- Exclude canceled (`InvoiceNo` starts with "C") transactions
- Feature engineering:
  - Calculate `TotalTransactionValue`
  - Convert date columns appropriately

### 2. Exploratory Data Analysis (EDA)
- Analyze top-performing countries by sales
- Monthly transaction trends
- Distribution of transaction values
- Customer segmentation and behavioral patterns

### 3. Model Building
- **Algorithms Used**:
  - Linear Regression
  - Random Forest Regressor
- **Performance Evaluation**:
  - Root Mean Squared Error (RMSE)
  - R² Score

### 4. Visualization
- Revenue and transaction heatmaps
- Distribution plots
- Prediction vs. Actual CLV scatterplots

---

## ▶️ How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/Runtimepirate/Customer_Lifetime_Value_Prediction.git
cd Customer_Lifetime_Value_Prediction
```
### 2. Download the Dataset
- Download the Online Retail Dataset from Kaggle
- Upload the dataset to your desired location (e.g., local folder or cloud storage such as Google Drive)
- Update the dataset path in the notebook to match your file location
### 3. Run the Notebook
- Open the file Customer_Lifetime_Value_Prediction.ipynb in Google Colab or Jupyter Notebook
- Run all cells sequentially
- Modify parameters, try different models, or extend the analysis as needed

## 📚 References
Dataset Source: Kaggle - Online Retail Dataset


