
# 🌟 Fandango EDA Data Science Project: Unveiling Movie Rating Discrepancies

Welcome to our comprehensive analysis of Fandango's movie ratings, where we explore potential biases and discrepancies in movie review systems.

## 🎬 Introduction

Welcome to the Fandango EDA Data Science Project, where we dive into movie ratings and ticket sales from 2015. This project applies data science skills to real-world data, focusing on the integrity and implications of online movie ratings.

## 🛠️ Project Focus

- **Real-World Application**: Apply theoretical knowledge to practical data analysis scenarios using real-world data.
- **Data-Driven Decision Making**: Collect, store, and analyze data to derive informed conclusions.
- **Critical Thinking**: Explore key questions about data relationships and implications.

## 💻 Technical Tools

- **Jupyter Notebook**: For coding and data analysis.
- **NumPy & Pandas**: Essential for data manipulation.
- **Matplotlib & Seaborn**: Tools for visualizing data insights.

## 🔍 Central Question

Investigate whether there is a conflict of interest for a website like Fandango that both sells movie tickets and displays review ratings.

## 🎥 Case Study: 2015

Analyze Fandango's dual role in selling movie tickets and displaying movie ratings, focusing on potential biases. "Taken 3" serves as a case example to assess discrepancies between ratings and movie quality.

## 📊 Analytical Approach

- **Rating Discrepancy Analysis**: Compare Fandango's displayed STARS and the actual RATING for movies to uncover inconsistencies.
- **Comparative Review Analysis**: Evaluate how Fandango’s ratings stack up against other review websites.
- **Data Scraping and Analysis**: Employ web scraping techniques to gather comprehensive review data for analysis.

---

## 📋 Executive Summary

This project investigates Fandango's movie rating system, examining discrepancies between displayed and actual ratings, and comparing these ratings with other movie review sites. The analysis uses data from 2015, including ratings from Fandango, Rotten Tomatoes, Metacritic, and IMDB.

## 📈 Methodology

1. **Data Collection & Preparation**:
   - Utilized `fandango_scrape.csv` for Fandango's ratings and `all_sites_scores.csv` for other sites.
   - Performed data cleaning and preparation, including normalization of ratings.

2. **Exploratory Data Analysis (EDA)**:
   - Explored datasets' structure and summary statistics using Pandas.
   - Created new columns, e.g., extracting the year from movie titles.

3. **Data Analysis & Visualization**:
   - Analyzed the correlation between a film's popularity and its ratings on Fandango.
   - Visualized the distribution of movie counts per year and the highest-rated movies.
   - Filtered out unreviewed films by investigating movies with zero votes.

4. **Comparative Analysis**:
   - Merged Fandango's dataset with other review sites' ratings.
   - Conducted comparative analysis to observe discrepancies and patterns.

5. **Statistical Analysis & Interpretation**:
   - Normalized ratings from all sites for comparability.
   - Analyzed the distribution of ratings across different sites, focusing on Fandango's ratings.

---

## 🔑 Key Findings

- **Rating Discrepancies**: Notable discrepancy between Fandango's displayed ratings and the actual ratings.
- **Comparison with Other Sites**: Fandango's ratings are consistently higher compared to Rotten Tomatoes, Metacritic, and IMDB.
- **Distribution of Ratings**: Fandango shows an uneven distribution, leaning towards higher ratings, whereas other sites have more balanced distributions.
- **Case Study - "Taken 3"**: Demonstrates how Fandango's ratings can mislead compared to other platforms.

![1](https://github.com/Vishnupriyaeupuri/EDA-Dashboarding-projects/assets/112987407/20c14203-fce9-4b21-b6f9-fa31a77627f5)
![2](https://github.com/Vishnupriyaeupuri/EDA-Dashboarding-projects/assets/112987407/422d6186-3550-4f1d-9673-03bf0d9e62f5)
![3](https://github.com/Vishnupriyaeupuri/EDA-Dashboarding-projects/assets/112987407/1ee8a4b5-f488-4def-bbe2-99b661df2b57)
![4](https://github.com/Vishnupriyaeupuri/EDA-Dashboarding-projects/assets/112987407/e594e9af-048b-45d9-acb2-f8965497c073)


## 📌 Implications

The findings suggest a potential bias in Fandango's rating system, raising questions about the reliability and integrity of online movie ratings on platforms that also sell movie tickets.

## 🏁 Conclusion

This analysis highlights the importance of critically evaluating online rating systems. It underscores the need for transparency and reliability in movie ratings and suggests consumers consult multiple sources when assessing film quality.
