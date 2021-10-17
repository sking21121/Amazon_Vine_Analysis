# Amazon_Vine_Analysis
Using my knowledge of PySpark I had to determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, 
I needed to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

## Results:

-How many Vine reviews and non-Vine reviews were there?

  The total number of Vine reviews were 285.
  The total number of non-Vine reviews were 31,545.
  
![total_reviews2](https://user-images.githubusercontent.com/86200136/137648418-87850a8c-ce53-412a-948c-097f35e6f13c.png)


-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  The number of 5 star Vine reviews were 163.
  The number of 5 star non_Vine reviews were 14,614.
  
  ![5star_reviews](https://user-images.githubusercontent.com/86200136/137648639-4f3208b8-e44f-429a-ab85-fb88de79d24a.png)

  
  -What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  
    Percentage of Vine reviews that were 5 stars: 57%
    
    Percentage of non-Vine reviews that were 5 stars: 46%
  
  
![percent_5star](https://user-images.githubusercontent.com/86200136/137648708-09892f79-ef61-49eb-91d0-a7d95229fe67.png)

### Summary:

The summary findings do indicate a positivity bias for Vine reviews versus non-Vine reviews. The final statistics shows 57%
of paid reviews gave a 5 star grade compared to 46% of non-paid reviews. One detail that must be acknowledged is
the fact that Vine rewiews data set is much smaller that non-vine reviews data set. So to compare the two data sets is not 
fair and we need more Vine data to reach a total conclusion.
