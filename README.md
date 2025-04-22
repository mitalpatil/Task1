# 📊 Netflix Data Analysis – Task 1

This project explores and analyzes the [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) using Python. The analysis includes data cleaning, transformation, descriptive statistics, and insightful visualizations using Matplotlib and Seaborn.

---

## 📁 Dataset

- **Source:** [Kaggle - Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File Used:** `netflix_titles.csv`

---

## ✅ Task Overview

The task was to:

1. Handle missing values and remove duplicates.
2. Transform and engineer useful data types and columns.
3. Perform basic data analysis (averages, counts).
4. Visualize findings using Matplotlib and Seaborn.
5. Submit a cleaned script with a brief report.

---

## 🧹 Data Cleaning Steps

- Handled missing values using `fillna()` with placeholder values or mode.
- Removed duplicate entries using `drop_duplicates()`.
- Converted `date_added` to `datetime` format.
- Extracted `year_added`, `month_added`, `duration_int`, and `duration_type` for analysis.

---

## 📊 Exploratory Data Analysis

Key insights from the dataset:

- **Movies** dominate the platform over **TV Shows**.
- Most content originates from **United States**, **India**, and **UK**.
- Common **ratings** include `TV-MA`, `TV-14`, and `R`.
- Average **movie duration** is ~99 minutes.
- Content additions peaked around **2019–2020**.

---

## 📈 Visualizations

The project includes the following charts:

- Bar Chart: Movies vs TV Shows
- Bar Chart: Top 10 Countries by Title Count
- Line Plot: Titles Added per Year
- Bar Chart: Top 10 Genres
- Bar Chart: Most Frequent Directors
- Bar Chart: Content Rating Distribution
- Heatmap: Titles Added by Year and Month
- Histogram: Distribution of Movie Durations

---

## 📂 Files Included

- `netflix_analysis.py` – Cleaned and complete Python analysis script
- `README.md` – This documentation
- *(Optional)* Jupyter Notebook version if desired

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – data manipulation
- **Matplotlib** & **Seaborn** – visualizations
- **NumPy** – numerical operations


---

## 🙌 Acknowledgments

- Dataset by [Shivam Bansal](https://www.kaggle.com/shivamb) on Kaggle
