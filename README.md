# Big_data

## Background:

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains more than 1.5 million rows. With more than 40 datasets, this can be quite taxing on the average local computer.

## Objectives:

*  Perform ETL on one of the review datasets.

*  Store your results on an AWS RDS database.

*  Determine if reviews are biased using PySpark or SQL with the appropriate statistical methods.

## Resources:
* schema.sql

* google chorme colab notebook

*  pyspark

*  AWS

* SQL

* Pgadmin

## link to analysis:




## Summary for Analysis:






#### Challenge Conclusion:
For Challenge, I used shoe data from amazon s3. I decided use a vine review to check biased or not?.First thing, I did make data frame one for vine review(Yes) and one for non vine review(no).Based on analysis, I got 895 total review for vine .and 4365429 non vine review.I did make 2 step anlysis.one step for vine and one step for non vine.

for vine review,I did make dataframe for vine review .I got 895 total review for vine.and then I started anlysis based on 1-5 star rating .They were total 462 for 5-star review rating .for more analysis, I decided with all star rating .They were total number total 328 for 4-star rating,total 75 for 3-star rating, total 25 for 2-star rating and total 5 for 1-star rating. Number is going down with star and also It was around 51% 5 star percentange out of total count.Based on star number and percentange ,I did decide to see 5-star rating for bias.They had around 51% 5-star review from out of total count. For statatics, see on table.They were mean around 2.3 of help full votes and 3.15 for total votes.Majority people were side on 5-star

![Screenshot (112)](https://user-images.githubusercontent.com/65969608/93726531-25634280-fb7c-11ea-8041-cd59d0d0a03d.png)


for non vine review,I did make dataframe for non vine(No) review.I got 4365429 total review for vine.and then I started analysis based on 1-5 star rating.They were total 2639077 5-star review rating .for more analysis, I did check with all star rating .They were total number total 847364 for 4-star rating, total for 404078 3-star rating, total 242794 for 2-star rating,total 232116 for 1-star rating. Number is going up with star and also It was around 60% for 5 star rating percentange from total count.Based on star number and percentange ,I did decide 5-star rating for bias. For more statatics, see on table. They were mean around 0.79 % for helpfull votes and 0.92% for total votes.Based on analysis, WE can tell that mostly people didn.t give their votes for review.

![Screenshot (113)](https://user-images.githubusercontent.com/65969608/93726539-3318c800-fb7c-11ea-8cfb-2300859e0e47.png)

For compare vine and non vine with 5 -star rating,Around 51% 's vote for vine(yes) review and around 60% vote for non vine(no) review.Number is going down in vine(yes).because of mostly people gave their votes to 5 -star rating and see on other side for non vine(no) review,Number is going up with down star. In non_vine review,bunch of people weren't give a review.When We see on 5-star rating with vine(yes) review , We could tell that vine aren't biased Because mostly people were side with 5 -star rating .but when we see on
other side on non vine(no)review,We could tell that vine are biased because mostly weren't gave their review.Now see on whole data ,We couldn't decided about for biased or not.For whole data ,We need require some more specification.
