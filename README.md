# 📊 Customer Churn Analysis – Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis on a bank’s customer dataset to uncover insights related to customer churn behavior. The goal is to identify key factors influencing churn and provide a foundation for future predictive modeling and customer retention strategies.

---

## 🧠 Objective

To analyze customer attributes and behavior to:
- Understand the main drivers of customer churn
- Identify important customer segments such as age groups and geography
- Support decision-making for targeted retention efforts

---

## 🔍 Key Insights

- **Age** is the strongest predictor of churn (correlation = 0.29). Older customers, especially those over 50, are more likely to leave.
- **Geography**: Customers in Germany have nearly twice the churn rate compared to France and Spain.
- **Balance** shows a weak positive correlation (0.12) with churn. High-balance customers (>200k) may need premium retention strategies.
- **Number of Products** has a weak negative correlation with churn, suggesting bundling may reduce attrition.
- **359 outliers** detected in Age, mostly older customers, which require further investigation.
- Credit Score and Estimated Salary show minimal impact on churn.

---

## 📁 Project Structure

churn-analysis/
├── churn_eda.ipynb # EDA notebook with analysis and visualizations
├── README.md # Project documentation
└── data/ # (Optional) Dataset files or samples

---

## 🛠️ Tools & Libraries Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Google Colab

---

## 📌 Next Steps

- Develop predictive models to forecast customer churn
- Evaluate model performance and key features
- Design targeted retention programs for high-risk groups such as older customers and German clients

---

## 📬 Contact

Connect with me on [LinkedIn](https://www.linkedin.com/in/s-m-abrar-hossain-asif-95627418a/) or open an issue for feedback and questions.
