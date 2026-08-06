# 🎬 Netflix Content Trends Analysis

Exploratory data analysis on a Netflix catalog dataset to uncover content strategy trends — genre popularity, Movies vs. TV Show distribution, and global content contribution by country.

## 📖 Problem Statement

Netflix operates in an increasingly competitive streaming market alongside Amazon Prime, Disney+, and regional OTT platforms. This project analyzes Netflix's content distribution to answer: **how has Netflix's content strategy evolved, and what does that reveal about audience preferences and global expansion opportunities?**

## 📂 Dataset

- **7,789 records**, 11 columns
- Attributes: title, director, cast, country, release date, rating, duration, and genre/type
- Coverage: content released between **2008–2021**

## 🎯 Objectives

- Analyze the distribution of Movies vs. TV Shows over time
- Identify the most common genres and how their popularity has shifted
- Compare country-wise contributions to Netflix's catalog

## 🧹 Data Cleaning & Feature Engineering

- Parsed `Release_Date` to datetime and extracted release year
- Handled missing values in `Director` and `Cast`
- Extracted a clean `Main_Genre` field from multi-label genre strings

## 📊 Key Visualizations

- **Line chart** — Movies vs. TV Shows released per year
- **Bar chart** — Top 10 genres on Netflix
- **Stacked bar chart** — Movies vs. TV Shows by top 10 countries
- **Choropleth map** — Global content distribution by country
- **Trend lines** — Growth of the top 5 genres over time

## 🔍 Key Findings

- Clear shift in content mix and genre popularity across the 2008–2021 window
- A concentrated set of countries dominate content contribution
- Findings support data-driven recommendations for future content acquisition and regional focus

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Plotly Express`

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn plotly
jupyter notebook Netflix_Data_Analysis.ipynb
```

## ✅ Conclusion

This analysis provides actionable insight into Netflix's evolving content strategy — highlighting genre and regional trends that can inform future content planning and global expansion decisions.

---
**Author:** [Nalin Kumar](https://github.com/nalinkumar2710) | Part of the AICTE–VOIS Conversational Data Analysis Virtual Internship (Sep–Oct 2025)
