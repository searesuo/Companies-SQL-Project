SQL Project Summary
This SQL project focused on exploring and analyzing a dataset named companies. The project demonstrated a variety of foundational and intermediate SQL techniques, organized into clear steps for data retrieval, filtering, and aggregation.

1. Data Exploration
The initial step retrieved the full dataset using SELECT * to get an overview of the companies table.

2. Basic Queries and Sorting
Queried specific columns like city and country.

Applied sorting using ORDER BY, and limited results with LIMIT to examine subsets of data (e.g., top 10 rows by company_id).

3. Filtering Data
Applied filters on both numeric and text-based columns:

Retrieved listings from specific countries (e.g., China, Japan, Chile).

Used pattern matching with LIKE to filter cities starting with "B" and not ending in "n".

Combined numeric and text filters (e.g., companies from China with company_id less than 500).

4. Handling Missing Data
Identified records with missing or non-empty city fields using conditions like city = '' and city != ''.

5. Aggregation and Grouping
Used aggregation functions such as COUNT, MAX, and MIN to:

Count distinct values in columns like city, country, and continent.

Identify the highest and lowest company_id.

Count the number of companies per country and per city (specifically within the United States), sorted by total listings.
