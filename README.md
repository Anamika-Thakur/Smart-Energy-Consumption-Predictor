# Smart Energy Consumption Predictor  
AI-Powered Smart Home Energy Optimization using Decision Trees

Smart Energy Consumption Predictor is a machine learning-based smart home system that predicts whether household energy consumption is High or Low using appliance usage, environmental conditions, and behavioral patterns.

Instead of predicting an exact energy value, the system focuses on identifying risky high-consumption situations and generating intelligent energy-saving recommendations.

The project simulates a virtual smart home assistant capable of understanding energy behavior and suggesting actions to reduce unnecessary power usage.

---

# Project Goals

- Predict high or low household energy consumption.
- Analyze smart home and weather-based behavioral patterns.
- Generate intelligent energy-saving recommendations.
- Build an end-to-end ML pipeline for smart sustainability systems.
- Demonstrate explainable AI using Decision Trees.

---

# Features Used

The model predicts energy consumption using:

- Appliance Energy Usage
- Indoor Temperature
- Outdoor Temperature
- Humidity
- Time of Day
- Weekend/Weekday
- Temperature Difference
- Weather Conditions

These features help the model understand human activity patterns and HVAC-related energy usage.

---

# Techniques Applied

- Decision Tree Classifier
- Feature Engineering
- GridSearchCV Hyperparameter Tuning
- Binary Classification
- Train/Test Split
- Feature Importance Analysis
- Smart Recommendation Engine


---

# How the System Works

The project follows a complete smart energy ML pipeline:

```text
Smart Home Sensor Data
        ↓
Data Cleaning & Processing
        ↓
Feature Engineering
        ↓
Decision Tree Prediction
        ↓
High / Low Consumption Detection
        ↓
Smart Recommendation Generation
```

---

# Smart Recommendation Examples

-  "Peak hours detected! Delay heavy appliance usage."
-  "Large indoor-outdoor temperature difference detected."
-  "Unnecessary appliance usage detected during low occupancy."

---

# Dataset

Dataset Used:
- Appliances Energy Prediction Dataset : https://www.kaggle.com/datasets/loveall/appliances-energy-prediction/data

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- kagglehub


---

# Model Performance

### Accuracy: 87%

## Classification Report

```text
                  precision    recall  f1-score   support

 Low Consumption       0.87      0.89      0.88      2127
High Consumption       0.87      0.85      0.86      1820

        accuracy                           0.87      3947
       macro avg       0.87      0.87      0.87      3947
    weighted avg       0.87      0.87      0.87      3947
```

The optimized Decision Tree model effectively identifies both high and low energy consumption patterns while maintaining balanced precision and recall.

---
