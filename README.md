# Amazon_Vine_Analysis

## Analysis Overview
   
   The purpose of this project was to analysis Amazon Vine program and determine
   whether there is a bias toward favorable reviews from Vine members. In this analysis,
   i used PySpark to perform and extract the dataset, transform the data, connect to an
   AWS RDS instance, load the process data into pgAdmin and calculate different metrics.
   My focused was on the US reviews for video games.

## Resource
    . Data Source: Amazon Review dataset, Video Games Revieew dataset
    . Software used: Google Colab Notebook, PostgreSQL, pgAdmin4, AWS
    
    
## Outcome

## Total number of reviews
      
     . Vine reviews 
         ![](images/paid_total_count.png)
         
         
         
         
         
         
         
     . Vine reviews
         ![](images/unpaid_total_count.png)

         
## Total number of 5-star reviews

      . Vine reviews
         ![](images/paid_five_star_count.png)
         
         
         
         
         
         
         
         
      . Vine reviews
         ![](images/unpaid_five_star_count.png)
         
         
         
## Percentage of 5-star reviews
      
      .Vine reviews
         ![](images/paid_five_star_percentage.png)
         
         
         
      .Vine reviews
         ![](images/unpaid_five_star_percentage.png)
## Summery

51% of the reviews in the Vine program were 5 stsrs reviews whereas the percentage 
in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the vine
program. In addition, we could analyse the statistical distribution mean, median and mode of the
star rating for the Vine and non-Vine reviews.
