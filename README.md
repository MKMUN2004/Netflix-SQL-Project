# Netflix-SQL-Project
In this project, I analyzed a Netflix dataset from Kaggle using SQL to extract insights on content trends. The dataset includes details like show ID, type (Movie or TV Show), title, director, cast, country, date added, release year, rating, duration, genres, and descriptions. I created a database in Microsoft SQL Server, imported the data, and wrote queries to answer 13 business questions. These covered things like counting movies vs. TV shows, finding the most common ratings, identifying longest movies, filtering content by directors or countries, analyzing genres, and categorizing content based on keywords in descriptions (e.g., labeling as 'Good' or 'Bad' if words like 'kill' or 'violence' appear). The goal was to demonstrate data querying skills for content moderation, recommendations, and platform growth analysis

# About the Project
Objective: Analyze and categorize Netflix content using structured querying techniques in T-SQL to extract insights on genres, country-wise production, release year distribution, and content categorization based on sensitive keywords (e.g., "kill", "violence").

Tools & Techniques: Utilizes MSSQL Server with Common Table Expressions (CTEs), aggregation functions (COUNT, AVG, MAX, MIN), window functions (ROW_NUMBER, RANK), STRING_SPLIT, DATEADD, CASE statements, and GROUP BY for data analysis.

Data Analysis Process: Involves data collection from Kaggle, table creation in MSSQL, data import via SQL Import Wizard, and interpretation using SQL queries.

Dataset: Includes metadata on TV Shows and Movies with attributes like show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description.

# Business Problems Solved
This project addresses 13 real-world business questions, including:

1. Count the number of Movies vs. TV Shows.
2. Find the most common rating for Movies and TV Shows.
3. List all Movies released in a specific year (e.g., 2020).
4. Identify the longest Movie.
5. Find content added in the last 5 years.
6. Find all Movies/TV Shows by director "Rajiv Chilaka".
7. List all TV Shows with more than 5 seasons.
8. Count the number of content items per genre.
9. Find each year and the average number of content releases in India, returning top 5 years.
10. List all Movies that are documentaries.
11. Find all content without a director.
12. Find how many Movies actor "Salman Khan" appeared in the last 10 years.
13. Categorize content based on the presence of keywords "kill" and "violence" in the description.

# Getting Started
Clone the repository: git clone <repository-url>.
Set up Microsoft SQL Server and restore the database using the provided schema.
Import the Netflix dataset (available on Kaggle) using the SQL Import Wizard.

Execute the SQL queries in the project to replicate the analysis.
