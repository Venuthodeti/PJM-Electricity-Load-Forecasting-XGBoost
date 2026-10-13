# ⚡ PJM Electricity Load Forecasting Using XGBoost

## 📌 Project Overview

This project focuses on forecasting hourly electricity demand using historical electricity consumption data from the PJM Interconnection region. It uses **XGBoost Regression**, a machine learning algorithm, to learn patterns in historical electricity usage and predict future energy demand.

The project includes data analysis, time-series feature engineering, model development, and a Streamlit application for interactive predictions.

## 🎯 Objectives

- Analyze historical hourly electricity consumption data.
- Identify patterns and trends in electricity demand.
- Perform data preprocessing and time-series feature engineering.
- Train an XGBoost regression model to forecast electricity load.
- Deploy the trained model through a Streamlit web application.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** XGBoost, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Web Application:** Streamlit
- **Development Environment:** Jupyter Notebook

## 📂 Project Structure

```text
PJM-Electricity-Load-Forecasting-XGBoost/
│
├── PJMW_MW_HOURLY_PREDICTIONS.ipynb
├── PJMW_MW_Hourly.xlsx
├── app.py
├── pjm_xgboost_model.pkl
├── xgb_features.pkl
├── requirements.txt
└── README.md
```

## 📊 Dataset

The project uses hourly electricity consumption data for the PJM West (PJMW) region. The dataset contains historical electricity load measurements, represented in megawatts (MW).

Historical load data helps identify recurring demand patterns and supports the development of a forecasting model.

## ⚙️ Methodology

1. **Data Loading:** Load the historical electricity consumption dataset.
2. **Exploratory Data Analysis:** Examine electricity demand trends and patterns.
3. **Data Preprocessing:** Prepare the dataset for machine learning.
4. **Feature Engineering:** Create relevant time-based and historical features, as implemented in the notebook.
5. **Model Training:** Train an XGBoost regression model.
6. **Model Evaluation:** Evaluate predictions using suitable regression metrics.
7. **Deployment:** Use the trained model in a Streamlit application to provide an interactive forecasting interface.

## 🚀 Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/Venuthodeti/PJM-Electricity-Load-Forecasting-XGBoost.git
cd PJM-Electricity-Load-Forecasting-XGBoost
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit application

```bash
streamlit run app.py
```

### 4. Explore the notebook

Open `PJMW_MW_HOURLY_PREDICTIONS.ipynb` in Jupyter Notebook to explore the analysis, model development, and forecasting workflow.

## 💡 Applications

- Electricity demand planning
- Energy resource management
- Historical consumption analysis
- Data-driven power system planning

## 👨‍💻 Author

**Venu Thodeti**

GitHub: [Venuthodeti](https://github.com/Venuthodeti)

## ⭐ Conclusion

This project demonstrates how machine learning and time-series analysis can be applied to electricity load forecasting. By combining historical consumption data with XGBoost regression, the project provides a foundation for data-driven energy demand prediction and interactive forecasting.


