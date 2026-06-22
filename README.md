# 🎬 Netflix Content Analytics Dashboard

This repository contains my Jupyter Notebook submission for **Project 5: Netflix Content Analytics Dashboard**, as part of the Data Science Internship curriculum (Group 3 - Data Analysis & Visualization Domain).

## 📌 Project Overview
The objective of this project is to explore and analyze Netflix's content catalog (Movies and TV Shows) to uncover trends, distribution patterns, and business insights. The project follows a complete Data Science workflow, from data cleaning to building advanced visual dashboards.

## 🚀 Key Features & Workflow

### 1. Data Cleaning Pipeline
* Fetched real-world Netflix dataset directly via URL.
* Handled missing values in crucial columns (`director`, `cast`, `country`).
* Cleaned and dropped rows with missing `date_added` and `rating`.
* Created derived features (`year_added`, `month_added`) for temporal analysis.

### 2. Exploratory Data Analysis (EDA) & Dashboards
Generated two comprehensive 2x2 and 1x3 dashboard grids using **Matplotlib** and **Seaborn**:
* **Content Distribution:** Pie chart comparing the volume of Movies vs. TV Shows.
* **Release Trends:** Line chart tracking content added from the year 2000 to the present.
* **Geographic Analysis:** Bar chart highlighting the top 10 content-producing countries.
* **Rating Demographics:** Countplot showing the distribution of content maturity ratings.
* **Duration Analysis:** Histogram mapping the distribution of movie lengths.
* **Content Strategy:** Heatmap correlating Content Type (Movie/TV Show) with Maturity Ratings.
* **Historical Shift:** Box plot showing the shift in release years between Movies and TV Shows.

### 3. Executive Insights
Extracted actionable business recommendations based on visual evidence, such as the dominance of TV-MA content and the average optimal runtime for movies.

## Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook (VS Code)

## 📂 How to View
Simply click on the `Project5_Netflix.ipynb` file in this repository to view the code, the generated dashboards, and the final executive report directly on GitHub.
