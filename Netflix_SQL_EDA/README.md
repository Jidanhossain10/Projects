# 📊 Netflix Movies and TV Shows Data Analysis using SQL

---

## 🧠 Overview

This project presents an end-to-end exploratory data analysis (EDA) of Netflix’s catalog of movies and TV shows using SQL. The primary aim is to uncover patterns and insights that can help understand Netflix’s content strategy and user offerings. By querying the dataset with SQL, we tackle real-world business questions that relate to content type, demographics, distribution, and content trends over time.

---

## 🎯 Objectives

- Examine the distribution between Movies and TV Shows.
- Identify the most common ratings for both content types.
- Analyze content based on:
  - Year of release
  - Country of production
  - Duration
- Extract and interpret content tagged with specific keywords or categories.
- Derive actionable insights and draw conclusions from the patterns observed.

---

## 🗃️ Dataset

- **Source**: [Kaggle - Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Contents**: Includes details like title, director, cast, country, date added, release year, rating, duration, genre, and description.
- **Format**: The analysis is performed using SQL queries on a structured version of the dataset.

> 📁 The `Netflix_EDA.sql` file contains all the SQL queries used in the analysis.

---

## 🔍 Key Business Questions Addressed

1. Count the number of Movies vs TV Shows
2. Find the most common rating for movies and TV shows
3. List all movies released in a specific year (e.g., 2020)
4. Find the top 5 countries with the most content on Netflix
5. Identify the longest movie
6. Find content added in the last 5 years
7. Find all the movies/TV shows by director 'Rajiv Chilaka'!
8. List all TV shows with more than 5 seasons
9. Count the number of content items in each genre
10. Find each year and the average numbers of content release in India on netflix and return top 5 year with highest avg content release!
11. List all movies that are documentaries
12. Find all content without a director
13. Find how many movies actor 'Salman Khan' appeared in last 10 years!
14. Find the top 10 actors who have appeared in the highest number of movies produced in India.
15. Categorize the content based on the presence of the keywords 'kill' and 'violence' in the description field. Label content containing these keywords as 'Bad' and all other content as 'Good'. Count how many items fall into each category.

---

## 🧾 Sample Insights & Findings

- 📈 **Movies dominate the Netflix catalog**, comprising over 70% of the content.
- 🌍 **The United States leads in content production**, followed by India and the United Kingdom.
- 🕒 **Most movies range between 90–120 minutes**, while TV shows often have 1 season listed.
- 🔞 **TV-MA** is the most common rating across the platform, indicating content targeted at mature audiences.
- 📅 **A noticeable surge in content occurred post-2015**, reflecting Netflix’s global expansion.
- 🗂️ Genre-specific keywords like “Crime”, “Drama”, and “Comedy” are among the most frequent.

---

## ✅ Conclusion

By utilizing SQL for this exploratory data analysis, we were able to answer essential business questions and uncover meaningful trends about Netflix's content strategy. The platform's focus on movies, mature-rated content, and an international content portfolio highlights its attempt to cater to a diverse global audience. This project serves as a practical demonstration of how structured querying with SQL can unlock powerful insights from large datasets.

---

