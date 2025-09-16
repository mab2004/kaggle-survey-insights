# Kaggle Survey Insights (2022)

This repository contains a data cleaning and insight generation project based on the **Kaggle Data Science Survey 2022**.  
The project demonstrates how to preprocess real-world survey data, handle missing values, encode categorical variables, and extract meaningful insights using Python.

---

## 📊 Project Overview
- **Dataset**: [Kaggle Machine Learning & Data Science Survey 2022](https://www.kaggle.com/competitions/kaggle-survey-2022)
- **Goal**: Clean the raw dataset, explore respondent demographics and preferences, and generate visual insights.
- **Skills Practiced**: Data cleaning, handling categorical data, exploratory data analysis (EDA), visualization, and reporting.

---

## 🛠️ Tools & Libraries
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔑 Key Steps
1. **Data Cleaning**
   - Removed duplicates and empty rows
   - Replaced blanks with NaN
   - Dropped columns with >50% missing values
   - Encoded categorical features

2. **Exploratory Analysis**
   - Age, gender, and country distributions
   - Education and student status trends
   - Coding & ML experience breakdown
   - Python usage among respondents

3. **Visualizations**
   - Count plots with hue comparisons
   - Correlation heatmap of encoded features
   - Compact “Top-5 Insights” dashboard

---

## 📌 Top 5 Insights
1. Majority of respondents fall in younger age groups (18–29).  
2. Male respondents form the largest gender group (~70%).  
3. Most responses came from India, USA, and Japan (top 3).  
4. Around 80% of respondents reported using Python regularly.  
5. Over 60% of respondents hold or are pursuing a **Bachelor’s/Master’s degree**.

---

## 📂 Repository Structure
```
├── kaggle_survey_cleaned.csv # Cleaned dataset
├── kaggle_survey_encoded.csv # Encoded dataset (categorical → numeric)
├── kaggle_survey_analysis.ipynb # Colab/Notebook with full code
└── README.md # Project documentation
```

---

## License

This project is licensed under the Apache License Version 2.0 - see the [LICENSE](LICENSE) file for details.
