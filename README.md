# 📈 Customer Churn Prediction & Retention Strategy

## 📌 Overview
This project applies **machine learning** to customer data from a fictional telecommunications company to predict **customer churn**. The core objective is to move beyond simply identifying churn by developing a robust predictive model. This model enables the company to proactively reach out to **at-risk customers** with targeted offers designed to persuade them to stay.

The analysis identifies the main factors driving customer attrition to guide smarter, data-driven retention decisions.

---

## 🎯 Objectives
* **Data Preprocessing**: Clean and prepare the Telco customer dataset, including handling missing values (11 entries in `TotalCharges`) and converting data types.
* **Exploratory Data Analysis (EDA)**: Explore the key factors (e.g., contract type, tenure, services) that have the biggest impact on a customer's likelihood to churn.
* **Model Building**: Build and compare different classification machine learning models to find the best performer for prediction.
* **Recommendation**: Select the most suitable model for real-world use and present clear, actionable insights to guide concrete business actions.

---

## 📊 Methods
* **Data Source**: The project utilizes the **Telco Customer Churn dataset** from Kaggle, with minor modifications.
* **Data Cleaning**: Missing values were removed (11 rows from over 5,000 entries). Numeric columns (`MonthlyCharges`, `TotalCharges`) were converted to the correct data type.
* **Analysis**: Visualizations (e.g., boxplots) were used to analyze feature dependencies, specifically comparing churn against key variables like `tenure`, `MonthlyCharges`, and `TotalCharges`.
* **Model Selection**: Multiple classification models were considered, with **Logistic Regression** ultimately selected as the final recommended model for its balance of performance and interpretability.
* **Libraries Used**: `numpy`, `pandas`, `matplotlib.pyplot`, and `seaborn`.

---

## 🔑 Key Results
The exploratory analysis revealed distinct characteristics of customers likely to churn:

* **Risk Factors**: Customers with **lower tenure**, **higher monthly charges**, and **lower total charges** are significantly more likely to churn.
* **High-Risk Segments**: The highest churn rates are associated with:
    * **Contract Type**: **Month-to-Month**.
    * **Internet Service**: **Fiber Optic**.
    * **Payment Method**: **Electronic Check**.
* **Final Model**: **Logistic Regression** was chosen as the most robust and useful model for prediction.

---

## 💡 Implications
* **Retention Focus**: The insights suggest that providing better **onboarding**, **early engagement**, or promotional contracts for **new customers** may be crucial to reducing churn.
* **Business Action**: The predictive model can be deployed to target interventions. A recommended decision **threshold between 0.1 and 0.3** is suggested, which can be adjusted based on the company's budget for retention offers and tolerance for false positives.

---

## 📁 Repository Structure
├── data/
│   └── churn_data_set_sample.csv # Input dataset (a sample or version of the data)
├── notebook/
│   └── customer_churn_analysis.ipynb # The main analysis and modeling notebook
├── README.md
└── LICENCE

---

## 🚀 Getting Started

### 1. Clone Repository
```bash
git clone <repository-url>
cd <repository-name>
```
### 2. Run Jupyter Notebook
Open the main notebook to view the complete analysis, cleaning steps, and model evaluation.

---

## 📚 References

[Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

[Scikit-learn Documentation](https://scikit-learn.org/stable/)

---

## 📝 License

Distributed under the MIT License. See LICENSE for details.

---

## ✉️ Contact

For more info and collaboration requests: connect with me on [LinkedIn](https://www.linkedin.com/in/asa-hellstrand/).
