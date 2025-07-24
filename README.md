# 📊 Predict Exam Score using Linear Regression

This project predicts a student's **final exam score** based on the number of **hours they study** using a **Linear Regression** model built with Python and scikit-learn.

---

## 🚀 Overview

- Input: Number of hours a student studies
- Output: Predicted exam score (formatted to 2 decimal places)
- Model: Simple Linear Regression using scikit-learn
- Dataset: Manually created sample dataset

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn (LinearRegression, train_test_split)

---

## 🧠 How It Works

1. Create a dataset of study hours vs exam scores
2. Split the data into training and testing sets
3. Train a `LinearRegression` model
4. Accept user input for study hours
5. Predict and display the score

---

## 💻 Sample Code Snippet

```python
user_input = float(input("Enter the number of Hours you Study :"))
predicted_score = model.predict([[user_input]])
print(f"Predicted Exam Score: {predicted_score[0][0]:.2f}")
