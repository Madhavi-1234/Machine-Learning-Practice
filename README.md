# Machine Learning Guide 🚀

A structured collection of Machine Learning concepts, practical implementations, experiments, and real-world projects. This repository documents my journey of learning and applying Machine Learning — from foundational concepts and algorithms to hands-on projects and model development.


This repository documents my Machine Learning learning journey through theoretical concepts, hands-on implementations, practical experiments, and end-to-end projects.

My focus is on developing a strong understanding of ML concepts by implementing algorithms, exploring real-world datasets, performing data analysis, and building practical machine learning solutions.

## 🚧 Currently Working On

### 🚗 US Accidents Dataset — Exploratory Data Analysis (EDA)

Currently working on an EDA project using the **US Accidents Dataset** to understand accident patterns and explore the relationships between different accident-related factors.

**Dataset Exploration & Analysis:**

- Explored the dataset structure, including rows, columns, data types, and column meanings.
- Analyzed numerical, categorical, datetime, and Boolean features.
- Performed missing-value analysis to identify incomplete and potentially unreliable columns.
- Investigated descriptive statistics, value distributions, and frequency patterns.
- Explored accident patterns based on states, cities, time, weekdays, and weather conditions.
- Used histograms, boxplots, and IQR-based analysis to investigate distributions and potential outliers.
- Started exploring relationships between weather-related features and accident severity.
- Investigated unusual patterns in `Distance(mi)`, `Wind_Speed(mph)`, and `Visibility(mi)`.

**Initial Observations:**

- Identified substantial missing values in selected weather and geographical columns.
- Observed highly concentrated values in the `Distance(mi)` feature.
- Investigated potential outliers in wind speed and visibility rather than automatically removing them.
- Explored preliminary relationships between wind speed, visibility, and accident severity.

**Current Focus:**
- Completing univariate, bivariate, and multivariate analysis.
- Investigating data quality issues and validating unusual observations.
- Developing meaningful EDA questions and interpreting analytical results.
- Preparing for feature engineering and subsequent ML implementation.

The current analysis uses an initial 5,000-row sample of the dataset. Findings will be further validated as the project progresses.

The complete project, including the Jupyter Notebook, Python implementations, visualizations, detailed analysis, and key findings, will be added after completion.

## 📌 Machine Learning Concepts & Projects

### 📊 Regression — Linear Regression

- Implemented Linear Regression from scratch and using libraries.
- Covered data preprocessing, model training, prediction, and evaluation.
- Practiced using NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.
- Explored relationships between input features and continuous output variables.

### 🧠 Classification — Logistic Regression

- Implemented Logistic Regression for classification.
- Covered data preprocessing, model training, prediction, and evaluation.
- Learned the fundamentals of binary classification and model evaluation.

### 🎓 Basic End-to-End Classification Project

**Placement Prediction using CGPA & IQ**

- Built a basic classification project using a Kaggle dataset.
- Used CGPA and IQ as input features to predict placement outcomes.
- Practiced the complete ML workflow, from data loading and preprocessing to model training and evaluation.

## 📂 Data Gathering & Data Understanding

- Reading and loading CSV datasets.
- Working with Pandas DataFrames.
- Understanding dataset structure and dimensions.
- Inspecting rows, columns, and data types.
- Exploring descriptive statistics.
- Identifying features and target variables.

### 👗 Fashion Style Classifier

- Built a Fashion Image Style Classification project.
- Worked with fashion image datasets and created custom style categories.
- Performed data preprocessing, class mapping, balancing, and train/validation/test splitting.
- Implemented a **CLIP-based hybrid style classifier** using PyTorch and Hugging Face Transformers.
- Used zero-shot classification along with a trained classification head.
- Achieved approximately **78.5% test accuracy**.
- Practiced real-world image classification and model evaluation.

### 📰 Fake News Detector — Exploratory Data Analysis

- Started a Fake News Detection project using a news dataset.
- Performed data loading and initial dataset understanding using Pandas.
- Analyzed dataset structure, columns, data types, and missing values.
- Explored the distribution of real and fake news labels.
- Analyzed news text length to understand differences between the classes.
- Performed basic text-based exploratory data analysis using Pandas and visualization libraries.
- Prepared the dataset for further text preprocessing and machine learning classification.

---

**Continuous Learning & Development**

This repository is continuously evolving as I strengthen my understanding of Machine Learning, explore new concepts, and implement practical projects.

More implementations, experiments, and project updates will be added as I progress.
