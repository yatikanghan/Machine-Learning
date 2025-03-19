# 🛍️ E-Commerce Customer Behaviour Analysis ML Project

[![Python](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4-green.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2-yellow.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.18-purple.svg)](https://plotly.com/)

## 👨🏻‍💻 Project Overview

 This project observed e-commerce customer behaviour in online shopping throughout my machine learning knowledge and techniques. Using a dataset of e-commerce customer behaviour, it obseved important aspects that influence online shopping and developing online shopping prediction models to enhance our business.


## 📌 Objectives

- Analyze customer behaviour, purchase habit and satisfaction level.
- Identify how customers attracted, and how enhance business opportunity.
- Observation of different value comparison so that we focuses on our actual customers.
- Focus on our targeted audience, and improve our sales.
- It Helps businesses archive their goals and optimize their valuable assets.

## 📈 Dataset

The dataset contains information about E-Commerce Customer Behaviour Dataset including:

- Customer ID - Integer
- Gender - String
- Age - Integer
- City - String
- Membership Type - String
- Total Spend - Numeric
- Items Purchased - Integer
- Average Rating - Numeric
- Discount Applied - Boolean
- Days Since Last Purchase - Integer
- Satisfaction Level - String

Source: [Kaggle - E-commerce Customer Behavior Dataset](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset)

##

## 📊 Exploratory Data Analysis (EDA) Insights  
Key insights extracted from the dataset:

- **Demographics:**
  - The average customer age is **33.60 years** with a broad age distribution.
- **Spending Behavior:**
  - Customers spend an average of **$845.38** per transaction.
  - Average number of items purchased per order: **12.6 items**.
- **Engagement Levels:**
  - Satisfaction Level Distribution:
    - **Satisfied**: 36.30%
    - **Neutral**: 30.66%
    - **Unsatisfied**: 33.24%
  - Average days between purchases: **26.59 days**.
- **Correlations:**
  - Strong relationships between **customer engagement, total spend, and purchase frequency**.
  - Customers with higher satisfaction tend to spend **$595.14**.

---

## 📋 Project Pipeline  
1️⃣ **Data Preprocessing**: Handle missing values, encode categorical features, and normalize numerical features.  
2️⃣ **Feature Engineering**: Identify key features influencing customer satisfaction and spending.  
3️⃣ **Model Selection & Training**: Train ML models like **Random Forest, XGBoost, and Logistic Regression**.  
4️⃣ **Evaluation**: Use **accuracy, precision, recall, RMSE, and F1-score** for performance assessment.  
5️⃣ **Deployment & Business Insights**: Generate recommendations for customer retention and marketing strategies.  

##

## ⚖️ Machine Learning Models Evaluated


| Model                 | Accuracy (%) | F1 Score (%) | Training Time (s) |
|----------------------|-------------|-------------|----------------|
| **Random Forest**    | **100.0%**   | **100.0%**   | 0.197          |
| **SVM**             | **100.0%**   | **100.0%**   | 0.008          |
| **Gradient Boosting** | **100.0%**   | **100.0%**   | 0.324          |
| **KNN**              | **98.6%**    | **98.6%**    | 0.003          |
| **Naive Bayes**      | **100.0%**   | **100.0%**   | 0.004          |
| **Logistic Regression** | **98.6%** | **98.6%** | 0.372          |

##

## 🗝️ Key Insights  
- The **average customer age** is **33.60 years**.  
- Customers spend an **average of $845.38 per transaction**.  
- **Average number of items purchased per order**: **12.6 items**.  
- **Satisfaction Level Distribution**:  
  - ✅ **Satisfied**: **36.10%**  
  - ⚠️ **Neutral**: **30.66%**  
  - ❌ **Unsatisfied**: **33.24%**  
- The **average days between purchases** is **26.59 days**.  
- **Customers with higher satisfaction spend $1273.50 on average**, while unsatisfied customers spend only **$595.14**.  

---
- 
##

## 🗣 Business Recommendations  
1️⃣ **Boost Retention** – Offer **5-10% discounts** or **loyalty perks** to **Neutral/Unsatisfied customers** to increase repeat purchases.  
2️⃣ **Personalized Marketing** – Identify **top spenders** and provide **VIP perks** & **targeted promotions** to maximize revenue.  
3️⃣ **Optimize Discounts** – Use **personalized discounting** to drive more purchases, especially for low-satisfaction customers.  
4️⃣ **Enhance Engagement** – Implement **email campaigns** for customers inactive for **30+ days** to re-engage them.  


## 🤖 Technologies Used

- Python 3.13
- Pandas & NumPy
- Plotly & Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🚀 Getting Started

1. Clone this repository
```bash
git clone https://github.com/yatikanghan/Machine-Learning.git
```

2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Open the Jupyter notebook
```bash
jupyter notebook jupyter/project.ipynb
```

## 📝 License

This project is licensed under the Apache 2.0 License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [Kaggle](https://www.kaggle.com/) for providing the dataset
- [Scikit-learn](https://scikit-learn.org/) for machine learning tools
- [Plotly](https://plotly.com/) for interactive visualizations

---
