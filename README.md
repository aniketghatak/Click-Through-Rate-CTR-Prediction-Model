# Click-Through Rate (CTR) Prediction Model

This project builds a machine learning model to predict whether a user will click on an advertisement based on their online behavior and demographics. The model uses a Random Forest Classifier and is trained on a real-world dataset.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:  
🔗 [Advertising Dataset](https://www.kaggle.com/datasets/gauravduttakiit/clickthrough-rate-prediction)

Features include:

- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Gender
- Clicked on Ad (Target)

---

## Model Overview

- **Model**: RandomForestClassifier
- **Data Split**: train_test_split (80% training / 20% testing)
- **Evaluation Metric**: accuracy_score
- **Library**: scikit-learn
- **Accuracy**: 96.15% on test data

## Input Features

- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Gender (1 = Male, 0 = Female)

---

## Usage

User is prompted to enter input values:

```python
Daily Time Spent on Site: 68.55
Age: 35
Area Income: 62000
Daily Internet Usage: 256
Gender (Male = 1, Female = 0): 1
```

Will the user click on the ad? → Yes
