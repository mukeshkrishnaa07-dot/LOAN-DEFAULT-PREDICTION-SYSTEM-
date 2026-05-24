# 💳 Loan Default Prediction System

## 📌 Project Overview

The **Loan Default Prediction System** is a Machine Learning and Data Analytics project designed to analyze borrower financial data and identify potential loan defaulters. Financial institutions face significant risks when borrowers fail to repay loans, leading to financial losses and increased Non-Performing Assets (NPAs).

This project uses Exploratory Data Analysis (EDA), Linear Regression, Risk Analysis, and Interactive Dashboard Visualization to understand borrower behavior and support better loan approval decisions.

The project demonstrates a complete workflow including:
- Data preprocessing
- Statistical analysis
- Data visualization
- Risk categorization
- Predictive modeling
- Dashboard creation

---

# 🎯 Objectives

The main objectives of this project are:

- Load and analyze loan borrower data
- Clean and preprocess the dataset
- Perform Exploratory Data Analysis (EDA)
- Identify patterns related to loan defaults
- Analyze borrower risk factors
- Build a Linear Regression model
- Evaluate model performance
- Create interactive visualizations and dashboards
- Support better loan approval strategies

---

# 📂 Dataset Information

## Dataset Source
- Kaggle Lending Club Loan Dataset

## Dataset Features Used

| Column Name      | Description                     |
|------------------|---------------------------------|
| loan_amnt        | Loan amount                     |
| term             | Loan duration                   |
| int_rate         | Interest rate                   |
| annual_inc       | Annual income                   |
| emp_length       | Employment length               |
| home_ownership   | Home ownership status           |
| purpose          | Loan purpose                    |
| grade            | Loan grade/risk level           |
| loan_status      | Loan repayment status           |

---

# 🛠 Technologies Used

| Technology      | Purpose                     |
|-----------------|-----------------------------|
| Python          | Programming Language        |
| Pandas          | Data Manipulation           |
| NumPy           | Numerical Operations        |
| Matplotlib      | Data Visualization          |
| Seaborn         | Statistical Visualization   |
| Plotly          | Interactive Dashboard       |
| Scikit-learn    | Machine Learning            |

---

# ⚙️ Project Workflow

## 1️⃣ Data Collection

- Load loan dataset
- Understand dataset structure
- Analyze columns and data types

---

## 2️⃣ Data Cleaning & Preprocessing

### Tasks Performed
- Handle missing values
- Remove unwanted symbols
- Convert categorical variables
- Convert data types
- Encode categorical columns

### Techniques Used
- Label Encoding
- Missing value handling
- String processing

---

## 3️⃣ Exploratory Data Analysis (EDA)

EDA helps understand borrower financial behavior and loan repayment trends.

### Analysis Performed
- Loan amount distribution
- Income distribution
- Interest rate analysis
- Default analysis
- Correlation analysis

---

## 4️⃣ Default Behavior Analysis

Comparison between:
- Fully Paid Loans
- Charged Off Loans

The project identifies:
- High-risk borrowers
- Loan repayment trends
- Financial risk indicators

---

## 5️⃣ Group-Based Analysis

### Income vs Default
Analyzes whether low-income borrowers are more likely to default.

### Employment Length vs Default
Studies how employment stability affects repayment behavior.

### Loan Purpose vs Default
Compares default rates across loan purposes.

### Home Ownership vs Default
Analyzes default behavior based on ownership status.

---

## 6️⃣ Relationship Analysis

### Relationships Studied
- Loan Amount vs Default
- Interest Rate vs Default
- Income vs Loan Amount
- Interest Rate vs Risk

---

# 📊 Data Visualization

The project includes several visualizations:

| Visualization Type | Purpose |
|--------------------|---------|
| Bar Charts         | Default distribution |
| Histograms         | Income & loan analysis |
| Scatter Plots      | Relationship analysis |
| Box Plots          | Outlier detection |
| Heatmaps           | Correlation analysis |

---

# ⚠️ Risk Analysis

Borrowers are categorized into:
- 🟢 Low Risk
- 🟡 Medium Risk
- 🔴 High Risk

Risk categories are determined using:
- Interest rate
- Income
- Loan characteristics

---

# 🤖 Machine Learning Model

## Linear Regression

### Independent Variables
- annual_inc
- int_rate
- term

### Dependent Variable
- loan_amnt

---

# 📈 Model Evaluation

The model is evaluated using:

| Metric | Description |
|--------|-------------|
| R² Score | Measures prediction accuracy |
| MAE | Mean Absolute Error |

---

# 📊 Interactive Dashboard

Interactive dashboard visualizations are created using Plotly.

## Dashboard Features
- Loan distribution charts
- Income vs Loan Amount
- Default comparison
- Risk category analysis
- Dynamic visualizations

---

# 📁 Project Structure

```bash
loan-default-prediction/
│
├── loan_default_prediction.py
├── README.md
└── requirements.txt
```

---

# ▶️ Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/loan-default-prediction.git
```

---

## Navigate to Project Folder

```bash
cd loan-default-prediction
```

---

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

---

# 🚀 Run the Project

```bash
python loan_default_prediction.py
```

---

# 📌 Sample Outputs

The project generates:
- Loan default distribution charts
- Income analysis graphs
- Correlation heatmaps
- Risk analysis results
- Model prediction outputs
- Interactive dashboard charts

---

# 🔍 Key Insights

- Higher interest rates indicate higher default risk.
- Annual income influences loan approval amount.
- Employment stability affects repayment behavior.
- Risk categorization helps detect potential defaulters.
- Loan purpose impacts default probability.

---

# 🔮 Future Improvements

Future enhancements may include:
- Logistic Regression
- Random Forest Classifier
- XGBoost
- Streamlit Web Application
- Real-time Dashboard
- Advanced Risk Prediction
- Deployment on Cloud Platforms

---

# 🎓 Learning Outcomes

This project helps understand:
- Data preprocessing techniques
- Exploratory Data Analysis
- Machine Learning workflows
- Regression models
- Data visualization
- Financial risk analysis

---

# ✅ Conclusion

The Loan Default Prediction System demonstrates how Machine Learning and Data Analytics can help financial institutions identify risky borrowers and improve credit risk management.

By combining EDA, predictive modeling, and interactive dashboards, the project provides valuable insights into borrower financial behavior and loan repayment patterns.

---

# 👨‍💻 Author

## Mukesh Krishna

---

# 📜 License

This project is created for educational and academic purposes.

---
