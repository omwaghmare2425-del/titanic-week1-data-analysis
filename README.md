# titanic-week1-data-analysis
Week 1 Data Acquisition, Cleaning and Exploratory Data Analysis using Titanic Dataset


## 📌 Project Overview

This project is completed as part of Week 1 of the Data Science with Python Internship.

The main objective of this project is to perform data acquisition, data cleaning, preprocessing, and exploratory data analysis (EDA) using the Titanic passenger dataset.

The project demonstrates a basic end-to-end data science workflow using Python.

---

## 🎯 Objectives

- Acquire a publicly available dataset
- Understand the structure of the dataset
- Identify missing values
- Handle missing values appropriately
- Check and handle duplicate records
- Verify data types
- Perform exploratory data analysis
- Create meaningful visualizations
- Identify important patterns and insights

---

## 📊 Dataset

The Titanic dataset contains information about passengers who travelled on the Titanic.

### Dataset Features

- `survived` – Survival status
- `pclass` – Passenger class
- `sex` – Passenger gender
- `age` – Passenger age
- `sibsp` – Number of siblings/spouses aboard
- `parch` – Number of parents/children aboard
- `fare` – Passenger fare
- `embarked` – Port of embarkation
- `class` – Passenger class category
- `who` – Passenger category
- `adult_male` – Adult male indicator
- `deck` – Deck information
- `embark_town` – Embarkation town
- `alive` – Survival label
- `alone` – Whether the passenger travelled alone

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

### Missing Values

Missing values were identified using:

```python
df.isnull().sum()
