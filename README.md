# Employee-Attrition-Predictor
This project focuses on analyzing employee data to identify the key factors that lead to resignations and build a machine learning model to predict future attrition.

Using HR data from various departments, we perform detailed Exploratory Data Analysis (EDA) to uncover trends related to salary, promotions, work-life balance, job satisfaction, and more. A Decision Tree classifier is then trained to predict whether an employee is likely to leave the company.

We also apply SHAP (Shapley Additive exPlanations) analysis to explain the model’s predictions and highlight which features contribute most to attrition risk. Finally, a Power BI dashboard is created to visualize insights in an interactive and business-friendly format.

## 🧠 Project Objective

🔹 Use analytics to understand the main causes of employee resignation  
🔹 Build a machine learning model to predict future attrition  
🔹 Provide insights to prevent high attrition rates  
🔹 Visualize data and model results using Power BI  

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: `Pandas`, `Seaborn`, `Scikit-learn`, `SHAP`
- **Visualization**: Power BI, Matplotlib
- **Model**: Decision Tree Classifier

---

## 📁 Project Structure

```

📦 employee-attrition-project/
├── data/
│   └── HR\_data.csv                  # Raw HR data (\~500 rows)
├── notebooks/
│   └── eda\_modeling.ipynb          # EDA + classification model
├── output/
│   ├── cleaned\_powerbi\_data.csv    # Power BI-ready data
│   └── shap\_summary\_plot.png       # Model interpretation plot
├── reports/
│   └── Employee\_Attrition\_Report.docx
├── README.md

```

---

## 🔍 Exploratory Data Analysis (EDA)

✅ Department-wise attrition  
✅ Attrition vs Salary Bands  
✅ Impact of promotions and job satisfaction  
✅ Correlation heatmaps for all key factors  

📌 *Findings*:
- Sales and Support have the highest attrition.
- Employees with low salary or no promotion in 5 years are more likely to leave.
- Poor work-life balance is a major red flag.

---

## 🤖 Classification Model

- **Model Used**: `DecisionTreeClassifier`
- **Accuracy**: ~86%
- **Evaluation**: Confusion Matrix + Classification Report

```

Confusion Matrix:
Predicted
\| No | Yes
Actual   No    | 112 | 13
Yes   | 14  | 61

````

---

## 💡 SHAP Analysis (Model Explainability)

We used SHAP to visualize which features contribute the most to predictions.

📊 Top Factors:
- OverTime
- YearsSinceLastPromotion
- JobSatisfaction
- MonthlyIncome
- WorkLifeBalance

> 🎯 SHAP helps HR understand *why* the model flags certain employees at risk.

---

## 📈 Power BI Dashboard

An interactive dashboard with filters and visual insights including:
- Attrition by Department, Age, Salary
- Monthly trends
- Attrition risk heatmaps

📤 **Data Source**: `cleaned_powerbi_data.csv` from this repo.

---

## ✅ Recommendations

🟢 Improve employee satisfaction  
🟢 Promote career development and training  
🟢 Offer better work-life balance policies  
🟢 Focus on high-risk departments like Sales and Support  
🟢 Address pay equity and offer timely promotions

> 📎 Detailed strategies in `Employee_Attrition_Report.docx`

---

## 📌 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/employee-attrition-project.git
cd employee-attrition-project

# Open the notebook
jupyter notebook notebooks/eda_modeling.ipynb
````

---

## 📬 Contact

Made with ❤️ by \[SASWAT]

📧 Email: [nayaksaswatranjan202@gmail.com](nayaksaswatranjan202@gmail.com)

🔗 [LinkedIn](https://www.linkedin.com/in/saswat13/)

---

```


