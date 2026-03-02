Here is a clean and professional **README.md** you can use for your Netflix / Media Dataset EDA Project 👇

---

# 🎬 Netflix / Media Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the Netflix / Media dataset using **Python and Matplotlib**.

The goal of this project is to analyze content trends, genre distribution, country contributions, and duration patterns of Movies and TV Shows available on Netflix.

This project demonstrates:

* Data Cleaning
* Data Visualization
* Feature Engineering
* Insight Generation
* Basic Machine Learning Model (Optional Section)

---

## 📂 Dataset Information

The dataset contains information about Netflix titles including:

* `type` (Movie / TV Show)
* `title`
* `director`
* `cast`
* `country`
* `date_added`
* `release_year`
* `rating`
* `duration`
* `listed_in` (Genres)
* `description`

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* NumPy
* Scikit-learn (for ML model)

---

## 📊 EDA Objectives

The following analysis was performed:

### 1️⃣ Data Cleaning

* Converted `date_added` to datetime format
* Extracted `year_added`
* Handled missing values
* Converted duration into numeric format

### 2️⃣ Content Type Analysis

* Distribution of Movies vs TV Shows
* Growth of content over time

### 3️⃣ Country Analysis

* Top 10 content-producing countries

### 4️⃣ Genre Analysis

* Top 10 most common genres

### 5️⃣ Rating Distribution

* Most common content ratings

### 6️⃣ Duration Analysis

* Movie runtime distribution
* TV Show season distribution

### 7️⃣ Release Year Trends

* Distribution of titles by release year

---

## 📈 Key Insights

* Netflix contains significantly more Movies than TV Shows.
* Content growth accelerated after 2015.
* United States produces the highest number of titles.
* Drama and International Movies dominate the genre list.
* Most movies are between 80–120 minutes.
* Most TV Shows have 1–3 seasons.

---

## 🤖 Machine Learning Model (Optional)

A Random Forest Classifier was trained to predict whether a title is:

* Movie
* TV Show

Using features:

* Release Year
* Duration

Model Evaluation:

* Accuracy Score
* Classification Report

---

## 🚀 How to Run the Project

1. Install required libraries:

```bash
pip install pandas matplotlib numpy scikit-learn
```

2. Place `netflix_titles.csv` in the project folder.

3. Run:

```bash
python eda_project.py
```

Or open in Jupyter Notebook and run all cells.

---

## 📁 Project Structure

```
Netflix-EDA/
│
├── netflix_titles.csv
├── eda_project.py
├── README.md
```

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How to clean real-world datasets
* How to perform exploratory data analysis
* How to generate meaningful visualizations
* How to build a simple classification model
* How to extract business insights from data

---

## 📌 Future Improvements

* Advanced feature engineering
* Sentiment analysis on descriptions
* Recommendation system
* Interactive dashboard (Streamlit / Power BI)
* Deep learning model

---

## 👨‍💻 Author

Meet Rupapara
Project – Netflix / Media Dataset EDA
Year – 2026

---

