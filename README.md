# Netflix vs Amazon Prime Video – Exploratory Data Analysis (EDA)

![Data Analysis](https://img.shields.io/badge/Data-Analysis-red.svg)
![Visualization](https://img.shields.io/badge/Data-Visualization-blueviolet.svg)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-lightgrey.svg)

![Google Colab](https://img.shields.io/badge/google-colab-orange.svg)
![Project Type](https://img.shields.io/badge/Project-Exploratory%20Data%20Analysis-purple.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)


## Project Overview
This project performs an Exploratory Data Analysis (EDA) on Netflix and Amazon Prime Video content catalogs. It explores differences in content types, genres, durations, and regional distribution using data visualization and statistical analysis techniques.

The project is part of my data analytics learning journey and focuses on extracting business insights from entertainment industry data.

---

## Business Objective
- Compare Netflix and Amazon Prime Video content strategies
- Identify genre and regional trends
- Analyze movie vs TV show distribution
- Study duration patterns across platforms
- Support data-driven content strategy decisions

---

## Dataset Overview

- **Source:** Public streaming platform catalog dataset  
- **Total Records:** 18,477 titles  
- **Attributes:** 16 metadata columns  
- **Platforms:** Netflix and Amazon Prime Video  
- **Time Period:** 1920 – 2024  
- **Regions:** USA, India, UK, Japan, and global content  

---

## Data Structure

| Column | Description |
|--------|-------------|
| show_id | Unique ID |
| type | Movie / TV Show |
| title | Content title |
| director | Director name |
| cast | Actors |
| country | Country of origin |
| date_added | Platform addition date |
| release_year | Year of release |
| rating | Content rating |
| duration | Duration (minutes/seasons) |
| listed_in | Genre |
| description | Content summary |
| platform | Netflix / Prime Video |

---

## Key Insights

### Content Distribution
- Movies dominate overall catalog
- Netflix has more TV shows
- Amazon Prime Video has more movies

### Genre Trends
- Drama is the most dominant genre
- Comedy and Action are highly popular
- Netflix has stronger documentary presence

### Duration Analysis
- Netflix average movie duration: ~99 minutes
- Prime Video average movie duration: ~91 minutes
- Netflix tends toward longer content

### Regional Insights
- USA is the largest content contributor
- India plays a key role in Prime Video content
- Netflix shows more global diversity

### Statistical Findings
- T-test confirms significant difference in durations
- ANOVA shows genre significantly impacts runtime
- Data contains mild skewness and outliers

---

## Key Recommendations

### Netflix
- Increase short-format content options
- Strengthen regional content (especially India)
- Balance TV show vs movie ratio

### Amazon Prime Video
- Invest in high-quality TV originals
- Expand premium long-format movies
- Improve global content diversity

### General Strategy
- Focus on high-performing genres: Drama, Action, Comedy
- Improve regional content expansion strategy
- Use data-driven content acquisition decisions

---

## Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (T-test, ANOVA)
- Jupyter Notebook
- Data Cleaning & Feature Engineering

---

## Project Structure

```text
EDA-Netflix-and-Prime-Video-Movies/
│
├── dataset/
├── notebooks/
├── visuals/
├── EDA.pdf
└── README.md
```

---

## Caveats & Limitations
- Dataset may not represent full platform catalogs
- Missing values were cleaned and imputed
- Some country data is incomplete
- Outliers may affect average calculations
- Post-2021 updates not included

---

## Conclusion
This project demonstrates how exploratory data analysis can uncover meaningful insights about content strategies across streaming platforms. It strengthens skills in data cleaning, visualization, and statistical analysis while supporting business-focused storytelling.

---

## Author
 HARITHA S  
 
 [ Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook ] 

[View Project PDF](https://github.com/06-10-2004/EDA-Netflix-and-Prime-Video-Movies/blob/main/EDA.pdf)
