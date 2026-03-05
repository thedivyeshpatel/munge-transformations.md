**Overview:**
This file documents the specific data cleaning and transformation steps applied to the raw video game sales dataset. These steps were executed using a single SQL query (via Hive) to perfectly mutate, filter, and arrange the data for the business problem.

**Transformations Performed:**
Table Creation & Selection: A new table named sales_genre was created from the original sales table. The query specifically isolated only the Genre, Global_Sales, and Critic_Score columns.

**Mutate:** The Global_Sales column was mutated by rounding the sales figures to the nearest whole number using the ROUND() function.

**Filter:** The dataset was filtered using a WHERE clause to exclusively include records where the Critic_Score was strictly greater than 0, successfully removing nulls and zero values.

**Arrange:** The final dataset was arranged in descending order (DESC) based on the Critic_Score, sorting the games from the highest-rated to the lowest-rated.
