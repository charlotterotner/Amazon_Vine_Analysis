# Amazon_Vine_Analysis

## Overview of the analysis:

The purpose of this analysis was to understand if paid reviewers were causing bias in overall review numbers for amazon furniture reviews. We used AWS, Postgres, and Spark to perofrm the analsyis   

## Results:

* **How many Vine reviews and non-Vine reviews were there?** For the furniture data set there were 136 paid Vine reviews and 18019 unpaid non-vine reviews.
* **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?** There were 74 paid vine 5 star reviews and 8482 unpaid non-vine 5 star reviews 
* **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?** 54% of the vine reviews were 5 stars and 47% of the non-vine reviews were 5 stars 

## Summary: 

Based off the results stated above I would say there is not positivity bias caused by the paid vine reviews. There was only a 7% difference in the percentage of 5 star reviews between the vine and non-vine reviewers. There was also a very small sample of vine reviews, so I do not think this caused bias for good reviews for Amazon furniture reviews. 

One additional analyses we could've done is look into 4 and 5 star reviews. Vine reviewers could be giving 4 star reviews which we did not consider in this analysis. Next time we could do a similar analysis but look at the same groups when the star_rating is greater than 3. This would give us more evidence to know whether or not the vine reviewers were causing positivity bias! 



