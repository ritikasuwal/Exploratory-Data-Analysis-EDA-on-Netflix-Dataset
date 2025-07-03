# 📊 Exploratory Data Analysis (EDA) on Netflix Dataset

Welcome to the **Netflix EDA Project**! This project aims to explore and analyze the Netflix Movies and TV Shows dataset using Python. The goal is to extract meaningful insights, detect trends, and visualize patterns in the content available on Netflix.

## 📁 Project Structure

---


--
## 🎯 Objectives

- Clean and preprocess raw Netflix datasets
- Handle missing values and convert formats
- Perform comprehensive exploratory data analysis
- Create visualizations to uncover trends and patterns
- Gain insights into content types, ratings, genres, and more

---

## 🧹 Data Cleaning & Preprocessing

### ✅ Tasks performed:
- Handled missing data in `director`, `cast`, `country`, `rating`, and `date_added`
- Converted `date_added` to datetime format
- Extracted `year_added`, `month_added` from `date_added`
- Separated `duration` column:
  - For Movies: extracted minutes
  - For TV Shows: extracted number of seasons
- Split `listed_in` into genres
- Removed duplicates and standardized column names
- Engineered new features like:
  - `is_movie` (Movie or TV Show)
  - `num_cast_members`
  - `num_genres`
  - `content_age` = Current Year − Release Year

---

## 📊 Exploratory Data Analysis (EDA)

### Key EDA Areas:
- **Distribution of content types**: Movies vs TV Shows
- **Content added over the years** (time trends)
- **Most frequent genres**
- **Top producing countries**
- **Most common ratings (TV-MA, PG, etc.)**
- **Top directors and actors**
- **Duration analysis** (longest/shortest content)

---

## 📈 Visualizations

Used `matplotlib`, `seaborn`, and `wordcloud` to create:

- Bar plots of content by type, year, country, rating
- Heatmaps for correlation and density
- Histograms of movie durations
- Word cloud of genres
- Boxplots for comparative duration analysis
- Time series plot of content addition trends

---

## 🧰 Technologies Used

- **Python**
- **Jupyter Notebook**
- **pandas** – for data manipulation
- **numpy** – for numeric operations
- **matplotlib** & **seaborn** – for visualization
- **wordcloud** – for genre analysis

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/ritikasuwal/Exploratory-Data-Analysis-EDA-on-Netflix-Dataset.git
cd Exploratory-Data-Analysis-EDA-on-Netflix-Dataset


