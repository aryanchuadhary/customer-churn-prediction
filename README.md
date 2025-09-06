# customer-churn-prediction
This project combines Machine Learning and Power BI to predict and visualize customer churn for a subscription-based business. It demonstrates how data-driven insights can help companies identify customers likely to churn and take proactive retention measures.

## 🔹 Key Features
- **Data Extraction:** Retrieve data from **SQL Server** using queries for preprocessing and analysis.
- **Data Preprocessing & Cleaning:** Handle missing values, categorical encoding, and feature engineering.
- **Machine Learning Model:** Random Forest classifier trained to predict customer churn.
- **Evaluation Metrics:** Confusion matrix, classification report, and feature importance analysis.
- **Power BI Dashboard:** Interactive visualizations for customer demographics, churn trends, revenue, and retention strategies.
- **Predictive Insights:** Predict churn for new customer data and highlight at-risk customers.

---

## 📊 Technologies Used
- **SQL Server:** Query and extract structured data
- **Python:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- **Power BI:** Interactive dashboards and visualizations
- **Machine Learning:** Random Forest Classifier
- **Data Storage:** Excel / CSV for intermediate data

---

## 📝 Dataset
- **Source:** SQL Server database
- **Columns:** Demographic info, subscription details, revenue, service usage, and customer status
- **Target Variable:** `Customer_Status` (Stayed, Churned, Joined)

> Note: A **sample dataset** is included for demonstration. Replace it with your own data from SQL Server.

---



📈 Model Performance
Accuracy: 83%

Confusion Matrix & Classification Report: See notebook for detailed metrics.

Feature Importance: Top features influencing churn are visualized
