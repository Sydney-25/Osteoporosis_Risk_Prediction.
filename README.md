# Osteoporosis Risk Prediction

## 1. Project Overview

The aim of this project is to develop a machine learning model to **predict the risk of osteoporosis in patients** using their medical records. Osteoporosis is a condition that weakens bones, making them fragile and more likely to break. The model is intended to identify individuals at risk, thereby enabling early intervention and prevention strategies.

---

## 2. Dataset

The dataset offers comprehensive information on health factors influencing osteoporosis development.

* **Key Features:** Demographic details (Age, Gender, etc.), lifestyle choices, medical history, and bone health indicators.
* **Data Dictionary (Partial):**
    | Column | Description |
    | :--- | :--- |
    | `ID` | Unique identifier for each patient |
    | `Age` | Age of the patient |
    | `Gender` | Gender of the patient |

---

## 3. Methodology

### 3.1. Exploratory Data Analysis (EDA)

EDA found that the following factors are significantly responsible for the risk of osteoporosis:

* Age
* Hormonal Changes
* Medical Conditions
* Medications
* Lifestyle and Nutrition

### 3.2. Models Evaluated

The following classification models were employed to predict the risk of osteoporosis:

* Logistic Regression
* Random Tree
* Decision Tree Classifier
* Support Vector Classifier (SVC)

### 3.3. Evaluation Metrics

Model performance was primarily assessed using **Accuracy**.

---

## 4. Results and Conclusion

The **Decision Tree Classifier** model yielded the best results in comparison to the others.

* **Accuracy:** Nearly **87%**.

The model provides a robust tool to predict the risk of osteoporosis, supporting medical professionals in enabling early intervention and prevention strategies.

---

## 5. Prerequisites

The analysis requires a Python environment with the following common data science libraries installed:

* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn` (`sklearn`)
