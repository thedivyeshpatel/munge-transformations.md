**Data Transformations (Munge Phase)**
**Overview:**
This file documents the data cleaning and transformation steps applied to the raw Video_Games_Sales_as_at_22_Dec_2016.csv dataset prior to analysis. These steps were originally completed as part of the Module 4 assignment.

**Transformations Performed:**
**Data Filtering:** The dataset was filtered to isolate records specifically related to the Sports and Shooter genres to align with the business problem.

**Handling Missing Values (Nulls):** - Records with missing Global_Sales data were removed or handled to ensure accurate sales aggregations. Records lacking a Critic_Score were identified and excluded from the average score calculations to prevent skewed results.

**Data Type Standardization:** Ensured that sales columns were properly formatted as numeric (float/decimal) data types rather than text to allow for mathematical aggregation in later steps.
