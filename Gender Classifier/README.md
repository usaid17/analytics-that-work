# 🧠 Gender Classifier (Using Decision Tree)

> A simple beginner machine learning model that predicts gender based on height, weight, and shoe size.

---

## 📌 Project Overview

This is my first machine learning project. It uses a small dataset and a **Decision Tree Classifier** to predict whether a person is male or female based on 3 physical features:

- Height (in cm)
- Weight (in kg)
- Shoe size

---

## 🗂️ Dataset

- File: `hight.csv`
- Format: CSV
- Features:
  - `Height`, `Weight`, `ShoeSize`, `Gender`
- Labels: `M` for Male, `F` for Female

🧪 The data is loaded directly from `hight.csv` using Python’s `csv` module.

---

## ⚙️ How It Works

1. Load and parse the dataset
2. Train a **Decision Tree model** using `scikit-learn`
3. Make predictions using new input values
4. Print out the predicted gender

---

## 🧪 Example Prediction

```python
prediction = clf.predict([[180, 90, 57]])
Output:
Male

📚 What I Learned
How to load data from a CSV file

Basics of feature and label separation

Training a Decision Tree using scikit-learn

Making predictions with a trained model

🛠️ Tools Used
Python

scikit-learn

csv (standard library)
