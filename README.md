# Sleep Disorder Classification

## 📌 Project Overview

This project analyzes sleep and lifestyle-related data to identify patterns associated with different sleep disorders. A **Random Forest Classification** model was developed to classify individuals into three categories: **No Sleep Disorder, Sleep Apnea, and Insomnia**.

The project demonstrates an end-to-end data analysis and machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model development, and evaluation.

---

## 🎯 Objectives

* Explore patterns and relationships between sleep, lifestyle, and health factors.
* Identify factors associated with different sleep disorders.
* Prepare and preprocess the dataset for machine learning.
* Engineer relevant features to improve model representation.
* Build a classification model to predict sleep disorder categories.
* Evaluate the model's classification performance.

---

## 📊 Dataset

The dataset contains information about individuals' demographic, lifestyle, sleep, and health characteristics.

### Key Variables

| Category     | Variables                                |
| ------------ | ---------------------------------------- |
| Demographics | Gender, Age, Occupation                  |
| Sleep        | Sleep Duration, Quality of Sleep         |
| Lifestyle    | Physical Activity Level, Daily Steps     |
| Health       | BMI Category, Blood Pressure, Heart Rate |
| Well-being   | Stress Level                             |
| Target       | Sleep Disorder                           |

### Target Classes

* **0 — No Sleep Disorder**
* **1 — Sleep Apnea**
* **2 — Insomnia**

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Scikit-learn** – Data preprocessing and machine learning
* **Google Colab** – Development environment

---

## 🔄 Project Workflow

### 1. Data Preparation

* Loaded the dataset using Pandas.
* Inspected the dataset structure and data types.
* Checked for missing values and duplicate records.
* Reviewed categorical and numerical variables.
* Prepared variables for analysis and modeling.

### 2. Exploratory Data Analysis

Analyzed relationships between sleep disorders and factors such as:

* Age
* Gender
* Sleep duration
* Quality of sleep
* Stress level
* Physical activity
* BMI category
* Heart rate
* Daily steps
* Blood pressure

Visualizations were used to identify distributions, patterns, and differences between sleep disorder groups.

### 3. Feature Engineering

A **Sleep-to-Stress Ratio** feature was created:

```python
sleep_stress_ratio = Quality of Sleep / (Stress Level + 1e-5)
```

This feature represents the relationship between an individual's sleep quality and stress level.

### 4. Data Preprocessing

Categorical variables were encoded into numerical representations, while numerical features were prepared for model training.

The target variable was encoded into three classes:

```text
0 → No Sleep Disorder
1 → Sleep Apnea
2 → Insomnia
```

### 5. Machine Learning Model

A **Random Forest Classifier** was used to predict the sleep disorder category.

Random Forest was selected because it can capture non-linear relationships between multiple health and lifestyle factors while providing a robust classification approach.

### 6. Model Evaluation

The model was evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

These metrics were used to assess how well the model distinguished between the three sleep disorder categories.

---

## 🔍 Key Analysis Areas

The analysis focused on understanding questions such as:

* How does sleep quality differ between individuals with different sleep disorders?
* Is higher stress associated with poorer sleep outcomes?
* How does sleep duration relate to sleep disorders?
* Are BMI and physical activity associated with sleep disorder patterns?
* Which characteristics help distinguish Sleep Apnea, Insomnia, and No Sleep Disorder?

---

## 💡 Key Takeaways

The project highlights how health and lifestyle variables can be analyzed together to identify patterns related to sleep disorders. It also demonstrates the importance of combining **exploratory data analysis with machine learning** rather than relying solely on model predictions.

> **Note:** The model is intended for educational and analytical purposes and should not be used as a medical diagnostic tool.

---

## 📁 Project Structure

```text
Sleep-Disorder-Classification/
│
├── Sleep_Disorder_Classification.ipynb
├── README.md
└── dataset/
    └── sleep_disorder.csv
```

---

## 🚀 Skills Demonstrated

**Data Analysis**

* Data cleaning
* Exploratory data analysis
* Statistical/pattern analysis
* Feature engineering
* Data interpretation

**Machine Learning**

* Classification
* Random Forest
* Feature preprocessing
* Model evaluation
* Confusion matrix analysis

**Technical Skills**

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab

---

## 👤 Author

**Kurt Aaron Delizo**
Aspiring Data Analyst | Computer Engineering Graduate

This project is part of my data analytics and machine learning portfolio.
