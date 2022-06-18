# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this analysis is to determine if there is any bias towards 5 star reviews for reviews written as part of the Vine program. The analysis was completed on the reviews dataset drawn from [Amazon Reviews US Video Games v1.00](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz). The dataset was filtered prior to calculations based on the following conditions, in order:
    - There were at least 20 total votes
    - The percentage of helpful votes is at least 50%

## Results
- How many Vine reviews and non-Vine reviews were there?
    - The dataset shows there 94 vine reviews and 40471 non-Vine reviews.
    [Vine Reviews](https://github.com/JorMerr/Amazon_Vine_Analysis/blob/main/img/vine_reviews.JPG)
    [Non-Vine Reviews](https://github.com/JorMerr/Amazon_Vine_Analysis/blob/main/img/non_vine_reviews.JPG)


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - The number of 5-star Vine reviews is 48 and the number of 5-star non-Vine reviews is 15663.
    [5-star Review Counts](https://github.com/JorMerr/Amazon_Vine_Analysis/blob/main/img/5-star_counts.JPG)

- What percentage of Vine reviews were 5 stars? What percent of non-Vine reviews were 5 stars?
    - The percent of Vine reviews that were 5 stars was approximately 51%.
    - The percent of non-Vine reviews that were 5 stars was approximately 39%.
    [5-star Review Percents](https://github.com/JorMerr/Amazon_Vine_Analysis/blob/main/img/5-star_percents.JPG)

## Summary
- The results of the analysis indicate that there may be positivity bias which is a result of the Vine program. The positivity bias is evidenced by the percentage of 5-star reviews for Vine reviews was 51%, compared the percentage of 5-star reviews for non-Vine reviews was 39%. It is possible, given the smaller dataset for Vine reviews that we may have a non-normal distribution of values which skew our results. 

- Additional analysis is recommended to determine the extent to which the Vine program shows positivity bias. Recommended means of conducting additional analysis are:
    - Conduct similar analysis of 5-star reviews on multiple datasets for Vine and non-Vine reviews.
    - Expand analysis to include percentage of 4 and 5-star reviews for Vine and non-Vine reviews.
    - Compare percentage of 1-star reviews for Vine and non-Vine reviews.