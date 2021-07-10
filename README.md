# Amazon_Vine_Analysis
### Overview
The goal of this project was to analyze Amazon reviews written by members of the paid Amazon Vine program. I picked a dataset of music reviews and performed the ETL process using PySpark. I connected to an AWS RDS instance and loaded the transformed data into pgAdmin. Next I used PySpark to determine if there was any bias toward favorable reviews from Vine members in the data set.

### Results
Total Reviews
-	Vine:  709
-	Non-Vine: 2,386,061

5 Star Reviews
-	Vine: 159
-	Non-Vine: 1,676,546

Percent of 5 Star Reviews
-	Vine: 22.43%
-	Non-Vine: 70.26%

### Summary
Based on that data that I have collected there is no positivity bias for reviews in the Vine program. Only about 22 percent of vine reviews were 5 stars compared to about 70 percent of non-Vine reviews. Another analysis that I think would be helpful would be to perform the same analysis, but with the one-star reviews.  
