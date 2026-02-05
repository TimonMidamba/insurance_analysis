# 🏥 Insurance Cost Analysis

## 📌 Project Overview
This project analyzes the factors that influence **medical insurance charges** using exploratory data analysis (EDA) and a baseline **Linear Regression model**.  
The goal is to understand which demographic and lifestyle features drive higher insurance costs and to communicate insights clearly using data.

This project is designed as a **portfolio project**, focusing on clarity, correctness, and learning progression rather than over-engineering.

---

## 🎯 Objectives
- Explore relationships between demographic features and insurance charges
- Identify the strongest drivers of high medical costs
- Visualize patterns and trends in the data
- Build a simple baseline regression model to predict insurance charges

---

## 📂 Dataset
- **Name:** Medical Insurance Dataset  
- **Source:** Public dataset commonly used for machine learning practice  
- **Size:** 1,300+ records  

### Key Features
- `age` – Age of the individual  
- `sex` – Gender  
- `bmi` – Body Mass Index  
- `children` – Number of dependents  
- `smoker` – Smoking status  
- `region` – Residential region  
- `charges` – Medical insurance cost (target variable)

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA focuses on understanding how different factors affect insurance charges.

### Key Analyses
- Distribution of age, BMI, and insurance charges
- Comparison of charges between smokers and non-smokers
- Relationship between age and charges
- Combined effects of smoking status and age

### Key Visualizations
- Boxplots for categorical comparisons
- Scatter plots for continuous relationships

---

## 📊 Key Insights
- **Smoking status is the strongest driver of high insurance charges**
- Insurance charges increase with age, especially for smokers
- BMI alone is not a strong predictor unless combined with smoking
- Non-smokers show more stable and lower charge distributions

---

## 📈 Linear Regression Model
A baseline **Linear Regression** model was built to predict insurance charges.

### Purpose
- Establish a simple baseline model
- Understand the linear relationship between features and insurance costs

### Notes
- The model is used for learning and interpretation, not production
- Results align with insights from the exploratory data analysis

---

## 🧠 Limitations
- Dataset size is relatively small
- No advanced feature enginee
