# 🚕 Taxi Price Prediction - Capstone Project
By **Michael Koffie**

## 📘 Project Overview
This project predicts taxi fare prices based on trip and time variables using multiple machine learning models.  
It was developed as part of the **Data Science Foundations to Core Career Track (Capstone 2)**.

## 🧠 Objective
Build predictive models and identify key factors influencing taxi fare amounts.

## 🧹 Data Preparation
- Cleaned and standardized numerical data
- Created dummy variables for categorical features
- Engineered time-based features (hour, weekday)

## 📊 Models Tested
| Model | MAE | MSE | R² |
|--------|-----|------|----|
| Linear Regression | 9.83 | 193.90 | 0.77 |
| Random Forest | 5.40 | 59.85 | 0.93 |
| Gradient Boosting | 4.95 | 56.61 | 0.93 |

✅ **Final Model: Gradient Boosting**  
Chosen for its accuracy and consistent performance.

## 💡 Key Insights
- Fare increases linearly with trip distance.
- Peak pricing observed during rush hours.
- Gradient Boosting achieved an R² of 0.93.

## 🚀 Recommendations
1. Implement dynamic pricing based on predicted fares.
2. Display pricing factor transparency to riders.
3. Incorporate additional features (weather, traffic) in future iterations.

## 📂 Repository Structure
# taxi-price-prediction-capstone
