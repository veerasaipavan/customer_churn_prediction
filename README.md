# **Customer Churn Prediction & Segmentation**  
An end-to-end Data Science & BI project using Python and Power BI to predict customer churn, understand churn drivers, and segment customers for targeted retention strategies.  

---

## 📌 Table of Contents
- [Objective](#objective)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Workflow](#project-workflow)
- [Sample Visuals](#sample-visuals)
- [Folder Structure](#folder-structure)
- [Key Insights](#key-insights)
- [Future Improvements](#future-improvements)
- [View Notebook](#view-notebook)
- [About Me](#about-me)

---

## **Objective**
- Predict the likelihood of customer churn using machine learning models.  
- Identify key factors influencing customer attrition.  
- Segment customers for targeted retention campaigns.  
- Visualize all business KPIs through a professional Power BI dashboard.  

---

## **Dataset**
- **File:** `Bank_Churn_Data.csv`  
- **Source:** Bank customer dataset  
- **Period:** Historical customer data  
- **Features:**  
  - **Demographics:** Customer ID, Age, Gender, Geography  
  - **Account Details:** Balance, Products, Credit Score  
  - **Activity:** Tenure, Active Member status  
  - **Target:** `Exited` (Churn Flag)  

---

## **Tools & Technologies**

| Component              | Tech Used                             |
|------------------------|---------------------------------------|
| Data Analysis          | Python (Pandas, NumPy)                |
| Visualization          | Power BI, Matplotlib, Seaborn         |
| Machine Learning       | Scikit-learn (Logistic Regression, Random Forest, XGBoost) |
| IDE                    | Jupyter Notebook                      |
| Data Cleaning & Export | csv + Python                        |

---

## **Project Workflow**

### **1. Data Cleaning**
- Removed missing and duplicate records.  
- Encoded categorical variables (`Geography`, `Gender`).  
- Feature scaling for numeric columns.  

### **2. Exploratory Data Analysis (EDA)**
- Churn rate by age group, geography, and account balance.  
- Identified churn-prone segments (e.g., low tenure, high balance inactive members).  
- Correlation heatmap to find strong predictors.  

### **3. Machine Learning**
- Train-test split for model validation.  
- Models tested: Logistic Regression, Random Forest, XGBoost.  
- Hyperparameter tuning using GridSearchCV.  
- Best model selected based on **ROC-AUC** and **F1 Score**.  

### **4. Customer Segmentation**
- Segmented customers into **High Risk**, **Moderate Risk**, and **Low Risk** categories based on churn probability scores.  

### **5. Dashboard (Power BI)**
- KPIs: Total Customers, Churn Rate, Active vs. Churned  
- Churn breakdown by geography, age group, and tenure  
- Feature importance visualization  
- Filters: Geography, Gender, Age, Tenure  

---

## **Sample Visuals**  
**Power BI Dashboard**  
![Dashboard](customer_churn_prediction/Screenshot2025-07-23160027.png)
![Customer Churn Dashboard](Screenshot%202025-07-23%20160027.png)

This interactive dashboard includes:  
- **Churn Rate:** 20.4%  
- **Total Customers:** 10,000  
- **High-Risk Customers:** ~1,800  
- Churn distribution by demographics and account details  
- Top churn drivers based on feature importance  

---

## **Folder Structure**
Customer_Churn_Prediction/
│
├── data/
│ └── Bank_Churn_Data.csv
├── notebooks/
│ └── churn_prediction_analysis.ipynb
├── dashboard/
│ └── powerbi_churn_dashboard.png
│ └── powerbi_churn_dashboard.pbix
├── output/
│ └── churn_predictions.csv
├── README.md
└── requirements.txt

---

## **Key Insights**
- Customers with low tenure and high balance are more likely to churn.  
- Geography and active member status are strong churn predictors.  
- France had the highest churn rate among countries in the dataset.  
- High-risk customers can be targeted with retention offers.  

---

## **Future Improvements**
- Automate churn prediction with a scheduled pipeline.  
- Integrate real-time scoring API for customer service teams.  
- Incorporate additional behavioral data (transactions, complaints).  
- Add retention campaign performance tracking in dashboard.  

---

## **View Notebook**
📄 [Open Jupyter Notebook](customer_churn_prediction_with_segmentation.ipynb.ipynb)  

---

## **About Me**
**Veera Sai Pavan Chavvakula**  
Aspiring Data Analyst | Skilled in Python, SQL, Power BI, and Machine Learning  
📧 [veerasaipavan6673@gmail.com](mailto:veerasaipavan6673@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/veera-sai-pavan-chavvakula-6260a72bb) 
