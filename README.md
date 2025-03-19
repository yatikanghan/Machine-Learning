# 🛍️ E-Commerce Customer Behaviour Analysis ML Project

[![Python](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4-green.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2-yellow.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.18-purple.svg)](https://plotly.com/)

## 👨🏻‍💻 Project Overview

 This project observed e-commerce customer behaviour in online shopping throughout my machine learning knowledge and techniques. Using a dataset of e-commerce customer behaviour, it obseved important aspects that influence online shopping and developing online shopping prediction models to enhance our business.

[CHECK IT OUT 🚀](https://c2p-cmd.github.io/online-gaming-behavior-analysis/)

## 🎯 Objectives

- Explore and analyze factors influencing online gaming engagement
- Identify key predictors of player engagement levels
- Build and compare various classification models
- Develop a robust model to predict engagement levels
- Provide actionable insights for game design and player retention

## 📊 Dataset

The dataset contains information about 40,000+ online game players including:

- Demographic data (age, gender, location)
- Gaming behavior (play time, session frequency, session duration)
- Progression metrics (player level, achievements unlocked)
- Monetization data (in-game purchases)
- Game preferences (genre, difficulty)

Source: [Kaggle - Online Gaming Behavior Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset)

## 🔍 Exploratory Data Analysis

The EDA reveals several key insights:

- **Demographics**: Players have a mean age of 31.99 years with broad distribution across age groups
- **Playtime**: Average weekly play time is 12.02 hours, with Action and Strategy genres having highest engagement
- **Engagement**: Medium engagement is most common (47%), followed by High (27%) and Low (26%)
- **Correlations**: Strong relationships between engagement and player level, achievements unlocked, and session metrics

## 🧮 Machine Learning Models

Several classification models were evaluated:

| Model | Accuracy | F1 Score | Training Time |
|-------|----------|----------|--------------|
| Random Forest | 91.0% | 91.0% | 2.03s |
| SVM | 90.9% | 90.8% | 7.03s |
| Gradient Boosting | 90.6% | 90.6% | 6.54s |
| KNN | 84.3% | 84.3% | 0.15s |
| Naive Bayes | 84.2% | 83.9% | 0.003s |
| Logistic Regression | 82.2% | 82.0% | 0.05s |

After hyperparameter tuning, the Random Forest model achieved the best performance with 91% accuracy and balanced precision/recall across all engagement levels.

## 🔑 Key Findings

1. **Behavioral metrics outweigh demographics**: Time-based metrics accounted for over 74% of predictive power
2. **Frequency over duration**: How often players engage (43%) matters more than session length (31%)
3. **Progression systems matter**: Player level and achievements showed moderate importance
4. **Minimal monetization impact**: In-game purchases had surprisingly little correlation with engagement

## 💡 Business Recommendations

1. **Design for frequent engagement**: Implement daily quests and consecutive login rewards
2. **Optimize session duration**: Structure game content for meaningful 90-95 minute sessions
3. **Enhance progression systems**: Make achievements and player levels more meaningful
4. **Rethink monetization strategy**: Focus on engagement-first design rather than purchase-driven features
5. **Targeted feature development**: Test new features based on predicted engagement impact

## 🛠️ Technologies Used

- Python 3.13
- Pandas & NumPy
- Plotly & Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🚀 Getting Started

1. Clone this repository
```bash
git clone https://github.com/c2p-cmd/online-gaming-behavior-analysis.git
cd online-gaming-behavior-analysis
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
