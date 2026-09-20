# 🔋 Machine Learning Project: Battery State of Health Prediction

> 🤖 A practical **Machine Learning** project focused on analyzing battery data and predicting **State of Health (SOH)** using Linear Regression.

---

## ✨ About the Project

In this project, Machine Learning techniques were used to analyze a battery dataset and study the relationship between different battery characteristics and **State of Health (SOH)**.

The main goal is to build a model that can predict the battery's health based on selected measured features. 🔋📊

---

## 🎯 Project Objectives

- 🔍 Explore and understand the battery dataset.
- 🧹 Check data quality, missing values, and duplicates.
- 📊 Analyze relationships between different variables.
- 🤖 Build Machine Learning models using **Linear Regression**.
- 📈 Compare model performance using evaluation metrics.
- 🧠 Understand how selected battery characteristics relate to **SOH**.

---

## 📁 Dataset

The dataset contains:

- **2,000 rows**
- **13 variables**

### Main Variables

| Variable | Description |
|---|---|
| 🔋 BatteryID | Battery identifier |
| 🏷️ BatchID | Batch identifier |
| 🔄 Cycle | Battery cycle number |
| ⚡ Voltage | Battery voltage |
| 🔌 Current | Battery current |
| 🌡️ Temperature | Temperature |
| ⏱️ ChargeTime | Charging time |
| ⏱️ DischargeTime | Discharging time |
| 🧲 InternalResistance | Internal resistance |
| 🔋 Capacity | Battery capacity |
| 💧 AmbientHumidity | Ambient humidity |
| ⚙️ C_Rate | Charge/discharge rate |
| ❤️ SOH | State of Health |

---

## 🔬 Project Workflow

### 1️⃣ Importing Libraries

The project uses several Python libraries, including:

- `NumPy`
- `Pandas`
- `Matplotlib`
- `Scikit-learn`

### 2️⃣ Data Exploration 🔎

The dataset was examined to identify:

- Number of rows and columns.
- Variable types.
- Missing values.
- Duplicate records.
- Descriptive statistics.

### 3️⃣ Data Analysis 📊

Different visualizations and analyses were performed to understand the dataset and explore relationships between the variables.

**Correlation Analysis** was also used to examine the strength of relationships between variables.

### 4️⃣ Building Machine Learning Models 🤖

**Linear Regression** was used to build models for predicting **SOH**.

Different combinations of battery features were tested to study how adding variables affects model performance.

### 5️⃣ Model Evaluation 📈

The models were evaluated using:

**MAE — Mean Absolute Error**

Measures the average absolute difference between the actual and predicted values.

**R² — R-squared**

Measures how well the model explains the variation in the data.

---

## 🧠 Tools & Technologies

🐍 **Python**

📊 **Pandas & NumPy**

📈 **Matplotlib**

🤖 **Scikit-learn**

📓 **Jupyter Notebook / Google Colab**

---

## 📓 Project Contents

```text
Machine-Learning-Project/
│
├── 📓 Machine_Learning_Project.ipynb
├── 📊 battery_dataset.csv
└── 📖 README.md