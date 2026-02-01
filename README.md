# Customer Intelligence & Churn Prediction System

## Project Overview
This project focuses on building an **end-to-end Customer Intelligence system** to analyze customer behavior, segment customers, predict churn using machine learning, and provide actionable business insights through an interactive dashboard.

The objective is to help organizations **identify high-risk customers proactively and reduce customer churn** using data-driven decision making.

---

## Project Objectives
- Build a **Customer 360 view** using cleaned and engineered data  
- Identify key **drivers of customer churn**  
- Segment customers based on behavior and value  
- Predict churn using **machine learning models**  
- Provide **business recommendations** to improve retention  

---

## Tools & Technologies
- **Python**: Pandas, NumPy  
- **Machine Learning**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- **Data Visualization**: Matplotlib, Seaborn  
- **Dashboarding**: Power BI  
- **Model Evaluation**:
  - ROC Curve
  - Precision-Recall Curve  
- **Version Control**: GitHub  

---

## Project Structure

Customer-Intelligence-System/
│
├── data/
│ ├── churn_dashboard_data.csv
│ └── customer_segmented.csv
│
├── notebooks/
│ ├── 01_customer_360.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_segmentation.ipynb
│ ├── 04_churn_prediction.ipynb
│
│
├── report/
│
└── README.md


---

## Project Workflow
1. Data Cleaning & Preprocessing  
2. Feature Engineering and Customer 360 Creation  
3. Exploratory Data Analysis (EDA)  
4. Customer Segmentation using K-Means  
5. Churn Prediction using Machine Learning  
6. Model Evaluation using ROC and Precision-Recall Curves  
7. Churn Risk Scoring  
8. Power BI Dashboard Development  
9. Business Insights and Recommendations  

---

## Machine Learning Models Used
- Logistic Regression (baseline model)
- Random Forest Classifier
- Gradient Boosting Classifier

Models were evaluated using:
- Accuracy
- ROC-AUC Curve
- Precision-Recall Curve

---

## Key Insights
- Customers on month-to-month contracts show the highest churn rate  
- New customers with low tenure are more likely to churn  
- Higher monthly charges significantly increase churn probability  
- Certain customer segments consistently show higher churn risk  

---

## Business Recommendations
- Encourage long-term contracts for high-risk customers  
- Provide targeted discounts to customers with high churn probability  
- Improve onboarding experience for new customers  
- Introduce loyalty programs for high-value customers  
- Use churn probability scores to trigger proactive retention actions  

---

## Future Enhancements
- Real-time churn prediction pipeline  
- Integration with live customer databases  
- Automated retention recommendation engine  
- Deployment using Streamlit or Flask  

---

## Author
- Rakshit Kumar
- Kreetika Kishore
