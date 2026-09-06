## 🚢 Titanic Survival Prediction ::


This repository contains a Jupyter Notebook (_titanic.ipynb) for a classic machine learning and data science project based on the Titanic dataset. The goal is to predict passenger survival using various machine learning techniques.
📁 Project Structure
📊 Dataset Information
The dataset used is from Kaggle’s Titanic: Machine Learning from Disaster. It includes details about the passengers such as:

PassengerId
Survived (Target variable)
Pclass (Ticket class)
Name
Sex
Age
SibSp (Siblings/Spouses aboard)
Parch (Parents/Children aboard)
Ticket
Fare
Cabin
Embarked (Port of Embarkation)
🧪 Project Workflow
The notebook covers the following steps:

Importing Libraries
Basic data analysis and ML libraries like pandas, numpy, matplotlib, seaborn, sklearn.

Data Loading & Exploration
Load CSV data, explore structure, identify missing values, and visualize key features.

Data Cleaning & Feature Engineering

Handling missing data (e.g., Age, Embarked, Cabin)
Encoding categorical variables (Sex, Embarked)
Creating new features (e.g., FamilySize, IsAlone)
Exploratory Data Analysis (EDA)

Correlation heatmap
Survival rate comparisons by class, sex, age
Visualizations using seaborn & matplotlib
Model Building

Train/Test split
Algorithms: Logistic Regression, Decision Trees, Random Forest, KNN, SVM
Model evaluation using accuracy, confusion matrix, cross-validation
Prediction

Predict on test data (if available)
Export results for submission
📈 Results
Accuracy measures how often the model correctly predicts whether a passenger survived or not. It is calculated as: Accuracy = (Number of Correct Predictions) / (Total Predictions) For example, if the model predicts correctly for 82 out of 100 passengers, the accuracy is 82%.

The notebook includes model evaluation and comparison. The best-performing model can be selected for final predictions based on accuracy or cross-validation scores.
🔧 Installation
To run the notebook locally:

Clone this repository
https://github.com/mayank341/DataScienceproject_titanicdataanalysis

📘 Explanation of Each Section:
Project Title & Overview

A catchy title (🛳️ Titanic Survival Prediction) and a brief intro describing what the repo is about.
Project Structure

Shows how your repo is organized, which is helpful for new contributors.
Dataset Info

Describes the data source and variables, crucial for understanding what you're working with.
Workflow

Detailed step-by-step outline of what your notebook does—makes your work reproducible and clear to readers.
Results

Mentions model evaluations. You can also add charts or accuracy metrics here if desired.
Installation

Instructions on how to run the notebook on someone else's system. This ensures anyone can use it easily.
Learn More

Resources for further reading.
Contributing

Invites collaboration and bug reports.
License

Defines how others can use your code. Default is MIT, but you can change it.

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
<img width="480" height="324" alt="Survival by gender" src="https://github.com/user-attachments/assets/6b41b00f-a57c-47f2-b38d-297c00999d2c" /># 
## 🧹 Data Processing

* Filled missing values (Age, Embarked)
* Dropped irrelevant columns (Cabin, Ticket, Name)
* Encoded categorical features
* Optional scaling

---<img width="480" height="324" alt="Survival by passenger class" src="https://github.com/user-attachments/assets/05ca4d8c-e17d-4db0-a68f-5075c3efac8a" />

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









---

## 🚀 Run Locally

```bash
git clone https://github.com/yourusername/titanic-prediction.git
cd titanic-prediction
pip install -r requirements.txt
jupyter notebook
```

---<img width="455" height="1352" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/ad0244b8-abef-46a9-b3a6-378a6009064c" />

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
