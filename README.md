

# Amazon_Vine_Analysis

Purpose:
The goal of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The service lets both manufacturers and publishers to receive reviews for their products. This allows companies to improve their products or services. The analysis encompasses large set of data processed in Amazon Cloud resources such as Managed Relational Database Services (RDS) and Amazon Simple Storage Service (S3). Also, the project leverages PostgreSQL and pgAdmin which is web-based GUI tool that is used to interact with the Postgres RDS instance in Amazon Web Services (AWS).

## Tools and Software: 
- Amazon S3, Amazon managed Relational Database Service (RDS), PostgreSQL 12.10, pgAdmin, Spark 3.2.2,  Google Colab, and Git Bash to commit changes into GitHub Repository.


# Results
Jennifer’s goal is to analyze all the reviews written by members of the paid Amazon Vine program. Jennifer and her colleague use latest cloud technologies to both store large amounts of dataset and transform and compute this data in short amount of time and provide the result of the analysis to the end user to make informed decisions.  Here are the steps taken by Jennifer and her colleague to analyze the data.

-	How many Vine reviews and non-Vine reviews were there? <br>
With the large dataset I’ve used, there are 6,878 Vine reviews and 6,924,287 non-Vine reviews<br>
![Count of Vine Reviews DataFrame](/Resources/Count_Vine_Reviews_df.png)<br>

![Count of Vine Reviews Database Query](/Resources/Count_Vine_Reviews_db.png)<br>

![Count of Non Vine Reviews DataFrame](/Resources/Count_Non_Vine_Reviews_df.png)<br>

![Count of Non Vine Reviews Database Query](/Resources/Count_Non_Vine_Reviews_db.png)<br>




-	How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? <br>
With the large dataset that I used, there are 543 Vine reviews with 5 star ratings and 112,803 non-Vine reviews with 5 star ratings.<br>

![Count of Vine Reviews with 5 Star DataFrame](/Resources/Count_Vine_Reviews_With_5_Stars_df.png)<br>

![Count of Non Vine Reviews with 5 Star DataFrame](/Resources/Count_Non_Vine_Reviews_With_5_Stars_df)<br>

-	What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? <br>
Percentage of paid Vine reviews with 5 stars were 0.4438305709023941 and percentage of non_Vine reviews with 5 stars were 0.4627093251066018<br>

![Percentage of Vine Reviews with 5 Star DataFrame](/Resources/Percentage_Vine_Reviews_With_5_Stars_df.png)<br>

![Percentage of Non Vine Reviews with 5 Star DataFrame](/Resources/Percentage_Non_Vine_Reviews_With_5_Stars_db.png)<br>



# Summary
The analysis done by Jennifer and her colleague did not find many positive bias since the percentage of paid Vine reviews is very close to the percentage of unpaid reviews with 5 star ratings.
- Here are the two percentage results. <br>

![Percentage of Vine and Non Vine Reviews with 5 Star DataFrame](/Resources/Determine_PaidReviews_UnpaidReviews_Percentages.png)<br>

- Here are two DataFrames where total votes are greater than or equal to 20 and greater than or equal to 50%<br>

![Total votes DataFrame greater than or equal to 20](/Resources/Create_TotalVotes_GT20_DataFrame.png)<br>

![Total votes DataFrame greater than or equal to 50 Percent](/Resources/Create_TotalVotes_GT_50Percent_DataFrame.png)<br>



## Links to images

Count of Vine Reviews DataFrame[Count_Vine_Reviews_df.png](https://github.com/bariir/Amazon_Vine_Analysis/tree/main/Resources/Count_Vine_Reviews_df.png?raw=true)<br>


Count of Non Vine Reviews DataFrame[Count_Non_Vine_Reviews_df.png](https://github.com/bariir/Amazon_Vine_Analysis/tree/main/Resources/Count_Non_Vine_Reviews_df.png?raw=true)<br>


Count of Vine Reviews with 5 Star DataFrame[Count_Vine_Reviews_With_5_Stars_df.png](https://github.com/bariir/Amazon_Vine_Analysis/tree/main/Resources/Count_Vine_Reviews_With_5_Stars_df.png?raw=true)<br>


Count of Non Vine Reviews with 5 Star DataFrame[Count_Non_Vine_Reviews_With_5_Stars_df](https://github.com/bariir/Amazon_Vine_Analysis/tree/main/Resources/Count_Non_Vine_Reviews_With_5_Stars_df.png?raw=true)<br>


Percentage of Vine Reviews with 5 Star DataFrame[Percentage_Vine_Reviews_With_5_Stars_df.png](https://github.com/bariir/Amazon_Vine_Analysis/tree/main/Resources/Percentage_Vine_Reviews_With_5_Stars_df.png?raw=true)<br>


Percentage of Non Vine Reviews with 5 Star DataFrame[Percentage_Non_Vine_Reviews_With_5_Stars_db.png](https://github.com/bariir/Amazon_Vine_Analysis/tree/main/Resources/Percentage_Non_Vine_Reviews_With_5_Stars_db.png?raw=true)<br>

