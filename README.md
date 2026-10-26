# 🎬 Netflix Content Analysis | SQL Project

## 📌 Project Overview

This project explores Netflix content data using SQL to uncover meaningful insights about movies and TV shows. The analysis focuses on content distribution, ratings, release years, countries, genres, directors, actors, and viewing duration.

Using MySQL, this project applies practical SQL techniques to answer business-oriented questions and demonstrate data analysis skills through structured queries.

## 🎯 Project Objectives

- Analyze the distribution of Movies and TV Shows.
- Identify common content ratings across different content types.
- Explore content by country, genre, and release year.
- Investigate directors and actors featured in the dataset.
- Examine movie durations and TV show seasons.
- Use conditional logic to categorize content descriptions.
- Solve real-world-style analytical questions using SQL.

## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Query Language:** SQL
- **Concepts:** Aggregations, Filtering, Sorting, Grouping, Subqueries, CTEs, Window Functions, String Functions, Date Functions, and CASE Statements

## 📂 Project Structure

```text
Netflix-SQL-Analysis/
│
├── netflix_project.sql
└── README.md
```

## 📊 Dataset Description

The project uses a Netflix content dataset stored in a MySQL database named `netflix_db`.

The main table is `netflix`, which contains the following fields:

| Column | Description |
|---|---|
| `show_id` | Unique content identifier |
| `type` | Movie or TV Show |
| `title` | Content title |
| `director` | Director's name |
| `cast` | Cast information |
| `country` | Country associated with the content |
| `date_added` | Date the content was added |
| `release_year` | Original release year |
| `rating` | Content rating |
| `duration` | Movie runtime or number of seasons |
| `listed_in` | Genre or category |
| `description` | Content description |

## 🔍 Business Questions & SQL Analysis

The project addresses 15 analytical questions, including:

1. How many Movies and TV Shows are available in the dataset?
2. What are the most common ratings for Movies and TV Shows?
3. Which movies were released in a selected year?
4. Which countries have the highest content counts?
5. Which movie has the longest duration?
6. What content was added within the last five years?
7. Which titles are associated with a specific director?
8. Which TV Shows have more than five seasons?
9. How is content distributed across genres?
10. How many titles from India were released in each year, and which years have the highest counts?
11. Which titles are categorized as documentaries?
12. Which records do not have director information?
13. How many movies featuring Salman Khan were released within the last ten years?
14. Which cast entries appear most frequently among Indian movies?
15. How can content descriptions be categorized using keywords such as “kill” and “violence”?

## 💡 SQL Skills Demonstrated

**Data Retrieval & Filtering**
- `SELECT`, `WHERE`, `LIKE`, `IS NULL`

**Data Aggregation**
- `COUNT()`, `GROUP BY`, `ORDER BY`, `LIMIT`

**Advanced SQL**
- Common Table Expressions (CTEs)
- Window functions such as `RANK()` and `AVG() OVER()`
- Subqueries
- `CASE` expressions

**Data Transformation**
- String manipulation using `SUBSTRING_INDEX()`
- Date conversion and date-based filtering
- Conditional categorization

## ⚙️ How to Run the Project

1. Install and open MySQL Workbench or another compatible MySQL client.
2. Download or clone this repository.
3. Open `netflix_project.sql` in the SQL editor.
4. Execute the script to create the database, create the table, and insert the sample records.
5. Run the analytical queries to explore the results.

**Note:** The SQL script uses MySQL-specific functions and syntax. Some date-related queries may require adjustments depending on the MySQL version and date formats.

## 📈 Key Learning Outcomes

- Translating business questions into SQL queries.
- Working with structured datasets and multiple content attributes.
- Applying aggregation and ranking techniques to compare categories.
- Using CTEs and window functions for more advanced analysis.
- Practicing date filtering, text matching, and conditional logic.
- Building a foundation for SQL-based data analytics projects.

## 🚀 Future Improvements

- Improve data quality by validating dates, release years, and missing values.
- Normalize country, cast, and genre information for more detailed analysis.
- Optimize queries and validate edge cases.
- Connect the dataset to Power BI or Tableau for interactive visualizations.

## 👨‍💻 Author

**Harshal Bavishi**

Aspiring Data Analyst | SQL | Excel | Power BI | Tableau | Python

---

⭐ If you find this project useful, feel free to explore the SQL queries and use them as a learning resource.
