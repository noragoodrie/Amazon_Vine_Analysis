# Amazon_Vine_Analysis

**OVERVIEW**
Amazon! What can't they do? This project was designed for us to analyze Amazon reviews written by members of the paid Amazon Vine Program. According the the moduled it was stated "The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review." So, my job was to dig deeply into this data and give the report of what we gathered!

We used PySpark, Google Collab and PGAdmin4! 

**RESULTS**

<img width="1339" alt="Screen Shot 2022-01-23 at 7 40 26 PM" src="https://user-images.githubusercontent.com/91299616/150718368-67bb6daa-dbd0-45b7-b21a-79f2786222a8.png">

In the above photo you are able to see the percent of votes DataFrame where we filtered the data to where the count of total votes are greater than or equal to 20! We also filtered it to where the percent of helpful votes to toal votes were greater than or equal to 50%! 

1. How many Vine reviews and non-Vine reviews were there?

- Vine Reviews: There were a total of 1080 reviews for the members.
- Non-Vine reviews: There were 49,650 total reviews for non-vine memembers.
- This shows us that more that 48,570 reviews were from non-vine memembers! (CRAZY!)

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- We can that 454 of the total reviews for vine were 5 star reviews.
- 23,034 reviews that were non-vine reviews were 5 star reviews.
- The total amount of 5 star reviews between the two are; 23,488.

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 42% of the reviews for Vine members were rated 5 stars.
- 46.4% of the reviews for Non-Vine members were rated 5 stars.

<img width="516" alt="Screen Shot 2022-01-23 at 7 45 17 PM" src="https://user-images.githubusercontent.com/91299616/150718718-0a8d2959-1cbd-426d-ac92-cdcfed00cd8e.png">

 **SUMMARY**
 
 In conclusion it is safe to say that there is no bias for the vine members, espesically when we look at how the 5 star to tal ratings are only less then 10 percent compaired to the non vine members! Something to consider when looking at this data is not filtering it out by 5 star reviews. 1,2,3 and 4 star reviews are more critical than any 5 star reviews are because they tend to be more informative for the company! 
