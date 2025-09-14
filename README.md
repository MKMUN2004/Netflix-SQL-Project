# Netflix-SQL-Project
Netflix dataset analysis using T-SQL
Netflix SQL Project

# Overview

This repository contains a SQL project analyzing the Netflix content dataset, curated by Muskan Agarwal. The project leverages Microsoft SQL Server to explore trends, filter by genres and countries, analyze release patterns, and extract insights on user preferences and platform growth. It showcases advanced SQL techniques to address real-world business problems.

# About the Project





# Objective: Analyze and categorize Netflix content using structured querying techniques in T-SQL to extract insights on genres, country-wise production, release year distribution, and content categorization based on sensitive keywords (e.g., "kill", "violence").



# Tools & Techniques: Utilizes MSSQL Server with Common Table Expressions (CTEs), aggregation functions (COUNT, AVG, MAX, MIN), window functions (ROW_NUMBER, RANK), STRING_SPLIT, DATEADD, CASE statements, and GROUP BY for data analysis.



Data Analysis Process: Involves data collection from Kaggle, table creation in MSSQL, data import via SQL Import Wizard, and interpretation using SQL queries.



Dataset: Includes metadata on TV Shows and Movies with attributes like show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description.

Business Problems Solved

This project addresses 13 real-world business questions, including:





Count the number of Movies vs. TV Shows.



Find the most common rating for Movies and TV Shows.



List all Movies released in a specific year (e.g., 2020).



Identify the longest Movie.



Find content added in the last 5 years.



Find all Movies/TV Shows by director "Rajiv Chilaka".



List all TV Shows with more than 5 seasons.



Count the number of content items per genre.



Find each year and the average number of content releases in India, returning top 5 years.



List all Movies that are documentaries.



Find all content without a director.



Find how many Movies actor "Salman Khan" appeared in the last 10 years.



Categorize content based on the presence of keywords "kill" and "violence" in the description.

Getting Started





Clone the repository: git clone <repository-url>.



Set up Microsoft SQL Server and restore the database using the provided schema.



Import the Netflix dataset (available on Kaggle) using the SQL Import Wizard.



Execute the SQL queries in the project to replicate the analysis.
