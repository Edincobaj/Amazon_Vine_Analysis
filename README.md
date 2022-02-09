# Amazon_Vine_Analysis

## Overview of the analysis
In this analysis we'll be using pyspark to extract, transform and load a large video game dataset of amazon reviews to see the determine if there is any bias toward favorable reviews from Vine members

## Results
1. How many vine reviews and non-vine reviews were there?
- There are 379 vine reviews and 73,701 non-vine reviews.
2. How many vine reviews were 5 stars? How many non-vine reviews were 5 stars?
- There are 211 5-star vine reviews and 30,908 5-star non-vine reviews.
3. What percentage of Vine reviews were 5 stars? What percentage of non-vine reviews were 5 stars?
- 5-star vine reviews account for 0.51% of all 5-star reviews while non-vine reviews account for 99.49% of all 5-star reviews.
![paid](https://user-images.githubusercontent.com/41974323/153113585-31a69c2a-546e-466d-9405-37c06a64ff63.PNG)
![unpaid](https://user-images.githubusercontent.com/41974323/153113593-ac583639-abee-435b-9c27-36e476caf3bd.PNG)

## Summary
Our analysis shows that there is not a positivity bias for reviews in the vine program. The results of our research shows that a much higher percentage of non-vine users (99.49%) rated video games 5-stars then vine users (0.51%). Though it is difficult to have high confidence in this analysis due to how much non-vine users outnumber vine users. Another analysis we can conduct to futher support and raise our confidence would be to take out any "Y" verified purchases during our data transformation. Due to most vine reviews being "N", this would help level the review numbers and give us a clearer picture on positivity bias.
