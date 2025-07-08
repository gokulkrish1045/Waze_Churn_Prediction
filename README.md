# 🚗 Waze Churn Prediction

A churn prediction analysis project using data from a fictional Waze-like navigation app. The goal is to identify potential churners and understand usage patterns using SQL and/or Python.

## 📌 Objective

Predict which users are likely to churn based on their activity history, engagement, and app usage.

## 🛠 Tools & Tech

- Python (Pandas, Matplotlib, Scikit-learn)
- Tableau
- Git & GitHub

## 📂 Project Structure
```bash
waze-churn-analysis/
├── data/ → Raw dataset CSVs
├── notebooks/ → logistic regression & tree based classification
├── visuals/ → Charts, graphs, screenshots
├── README.md → You're here
├── .gitignore 
```

## 🔍 Key Steps

- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building 
- Final Insights & Recommendations

## 📊 Sample Insights

- Users who drive less than 5km/day have a 60% higher churn rate
- Weekend-only drivers are more loyal
- Churn peaks after new version rollouts

## 🖼 Visuals


## 1,LOGISITC REGRESSION OUTPUTS:

### LOGISIC REGRESSION CONFUSION MATRIX ACHIEVED F1 SCORE 9%:
![CM](visuals/logistic_regression_CM.png)

<p align="center">
  <img src="visuals/logistic_regression_CM.png" style="background-color: white; padding: 10px;" />
</p>


### LOGISTIC REGRESSION FEATURE IMPORTANCE BAR CHART:

![FEATURE_IMPORTANCE](visuals/logistic_feature_importance.png)

### CHAMPION MODEL XG_BOOST  CONFUSION MATRIX ACHIEVED F1 SCORE 49%:
![CM](visuals/xg_boost_CM.png)

### XG_BOOST MODEL FEATURE IMPORTANCE BAR CHART:

![FEATURE_IMPORTANCE](visuals/xg_boost_feature_importance.png)

## 💡 Conclusion

This analysis helps Waze teams identify at-risk users, optimize app features, and reduce churn.

## 🧠 Author

- Gokula Krishnan  
- [LinkedIn](https://www.linkedin.com/in/gokula-krishnan-senthilkumar-70a824212)  
- [Portfolio](https://gokulkrish1045.github.io/goku1045/)

