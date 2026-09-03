<img width="480" height="324" alt="Survival by gender" src="https://github.com/user-attachments/assets/6b41b00f-a57c-47f2-b38d-297c00999d2c" /># 🚢 Titanic Survival Prediction

## 📌 Overview

A Machine Learning project that predicts whether a passenger survived the Titanic disaster using structured data like age, gender, and ticket class.

> 🎯 Goal: Build a reliable classification model with strong real-world ML workflow practices.

---

## 🧠 Problem

Predict:

* **0 → Did not survive**
* **1 → Survived**

Type: **Binary Classification**

---

## ⚙️ Tech Stack

**Language**

* Python

**Libraries**

* pandas, numpy → data handling
* matplotlib, seaborn → visualization
* scikit-learn → ML models
* joblib/pickle → model saving

---

## 📊 Dataset Features

| Feature  | Meaning          |
| -------- | ---------------- |
| Pclass   | Ticket class     |
| Sex      | Gender           |
| Age      | Age              |
| SibSp    | Siblings/Spouses |
| Parch    | Parents/Children |
| Fare     | Ticket price     |
| Embarked | Boarding port    |

---

## 🔍 Key Insights

* Females had much higher survival rates
* 1st class passengers survived more
* Children had better chances
* Higher fare → higher survival probability

---

## 🧹 Data Processing

* Filled missing values (Age, Embarked)
* Dropped irrelevant columns (Cabin, Ticket, Name)
* Encoded categorical features
* Optional scaling

---

## 🤖 Models Used

* Logistic Regression
* Decision Tree
* Random Forest ✅ (best)

---

## 📈 Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~80%     |
| Decision Tree       | ~78%     |
| Random Forest       | ~84%     |

---

## 🔄 Workflow

```
Data → Cleaning → EDA → Feature Engineering → Model → Evaluation → Prediction
```
<img width="480" height="324" alt="Survival by gender" src="https://github.com/user-attachments/assets/df5220fb-7542-4be6-a8af-d0fd7509303e" />



<img width="480" height="324" alt="Survival by passenger class" src="https://github.com/user-attachments/assets/05ca4d8c-e17d-4db0-a68f-5075c3efac8a" />


<img width="455" height="1352" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/ad0244b8-abef-46a9-b3a6-378a6009064c" />



---

## 🚀 Run Locally

```bash
git clone https://github.com/yourusername/titanic-prediction.git
cd titanic-prediction
pip install -r requirements.txt
jupyter notebook
```

---

## 🧪 Example

**Input**

```json
{
  "Pclass": 1,
  "Sex": "female",
  "Age": 29,
  "Fare": 100
}
```

**Output**

```
Survived ✅
```

---

## 🔮 Future Scope

* FastAPI backend
* React frontend
* Model tuning (XGBoost)
* Deployment

---

## 🙌 Final Note

This project covers a full ML pipeline — from raw data to prediction — and is a solid base for real-world ML systems.

---
