# 📊 Exploratory Data Analysis (EDA) on Netflix Dataset

Welcome to the **Netflix EDA Project**! 
This project uses two datasets to explore and analyze the movies and TV shows available on Netflix. Using powerful data visualization and sentiment analysis tools, it uncovers trends, patterns, and content insights.

## 🎯 Objectives

- Perform data cleaning and preprocessing on both datasets
- Conduct exploratory data analysis (EDA) using Python
- Visualize key insights with Plotly and Seaborn
- Analyze content trends across genres, ratings, years, and countries
- Apply sentiment analysis to descriptions using TextBlob

---
## 🧰 Technologies Used

| Tool / Library | Purpose                     |
|----------------|-----------------------------|
| `Python`       | Main programming language   |
| `pandas`       | Data manipulation           |
| `numpy`        | Numerical operations        |
| `matplotlib` & `seaborn` | Data visualization |
| `plotly.express` | Interactive visualizations |
| `textblob`     | Sentiment analysis          |
| `Jupyter Notebook` | Development environment  |

---
### ✅ Tasks performed:

- Cleaned null values and handled missing data  
- Separated multiple values in columns like *genre*, *country*, and *cast*  
- Extracted release year and calculated additional time-based insights  
- Counted and compared Movie vs TV Shows  
- Explored ratings distribution and genre popularity  
- Analyzed country-wise production trends  
- Identified top directors by content volume  
- Analyzed movie durations and TV show seasons  
- Created interactive plots with Plotly  
- Applied sentiment analysis on content descriptions using TextBlob  
- Visualized polarity and sentiment trends over time and across genres  

## 📊 EDA Highlights

✔️ Distribution of Movies vs TV Shows  
✔️ Most common ratings (TV-MA, PG, R, etc.)  
✔️ Content released by year and added by year  
✔️ Top genres and multi-genre breakdown  
✔️ Country-wise content trends  
✔️ Top 5 directors with the most content  
✔️ Duration insights (Movie runtime & TV seasons)

---

## 📈 Visualizations

Used `matplotlib`, `seaborn`, and `wordcloud` to create:

- Bar plots of content by type, year, country, rating
- Histograms of movie durations
- Boxplots for comparative duration analysis
- Time series plot of content addition trends

---
## 💬 Sentiment Analysis

Used the `description` column from the dataset to perform sentiment analysis using **TextBlob**.

- **Polarity** scores from `-1` (negative) to `+1` (positive)
- Each show/movie classified as:
  - `Positive`
  - `Neutral`
  - `Negative`

**Sentiment Insights Visualized By:**
- Content type (Movie vs TV)
- Release year
- Genre

---


## 🚀 How to Run This Project

1. **Clone the repository**
```bash
git clone https://github.com/ritikasuwal/Exploratory-Data-Analysis-EDA-on-Netflix-Dataset.git
cd Exploratory-Data-Analysis-EDA-on-Netflix-Dataset

