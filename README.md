***

# Introduction to Data Science (University of Maryland)

Welcome to my CMSC320 repository where I've compiled a series of data science analyses and project reports. These projects explore *real-world* datasets, focus on hypothesis-driven exploration, and apply statistical and machine learning techniques to answer meaningful questions.

***

## 📊 Contents

**1. Planet Terp Analysis**
- Examines University of Maryland professor ratings using publicly available data on PlanetTerp.
- **Approach:** Scraped reviews, grade distributions, and ratings for 13k+ professors; built a Pandas DataFrame for analysis.
- **Questions Answered:**
  - How do grade distributions relate to a professor's rating?
  - Do withdrawal rates reflect perceived teaching quality?
  - Can we predict ratings using only objective features (grades/withdrawals/sentiment)?
- **Techniques:** Linear Regression, Random Forest, Support Vector Regression, Ridge Regression.
- **Highlights:** Random Forest provided the best predictions; sentiment in reviews is highly influential. Grades alone don't fully explain perceived teaching quality.

**2. Exploring Attendance Patterns**
- Investigates how weather impacts lecture attendance for CMSC320.
- **Approach:** Merged daily attendance data with local meteorological records.
- **Questions Answered:**
  - Does rain or temperature change class attendance?
  - Do students attend more right before exams?
- **Techniques:** Data cleaning, linear regression, hypothesis testing, correlation analysis.
- **Highlights:** Rainy days showed a slight decrease in attendance, but this wasn't statistically significant. No meaningful effects from temperature or exam periods in the existing dataset.

**3. Exploring Morality through Data Science**
- Analyzes how data science students judge moral scenarios, using survey responses.
- **Approach:** Studied how age, time, and day of week affect moral judgments in hypothetical "Am I A Jerk?" scenarios.
- **Questions Answered:**
  - Does age influence moral harshness?
  - Are students more lenient when they relate to a scenario?
  - How do judgment patterns change by time of day, week, or class section?
- **Techniques:** Survey data cleaning, grouping/comparison, t-tests, visualization.
- **Highlights:** Younger students were more judgmental in 2025 (compared to 2024). Judgments are most harsh late at night/midweek. Small differences appeared between class sections; morality tends to be situational and context-dependent.

***

## 🚀 Key Concepts and Skills

- Data wrangling, cleaning, and merging from APIs and CSVs
- Statistical hypothesis testing, linear regression, and correlation analysis
- Supervised machine learning and model interpretation
- Visualization (matplotlib, seaborn)
- Ethical and behavioral analysis using survey data

***

## 📁 Project Organization

- `Planet_Terp_Analysis.pdf` - Full writeup and code for UMD professor review prediction
- `CMSC320_HW_6-1.pdf` - Statistical analysis of attendance patterns and weather
- `Exploring_Morality_through_Data_Science.pdf` - Behavioral data analysis and moral decision survey

***
