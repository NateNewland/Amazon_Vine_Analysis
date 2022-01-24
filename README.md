# Amazon_Vine_Analysis
# Overview and Summary
Many of Amazon's shoppers depend on product reviews to make a purchase. The first goal for this project was to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal was to use PySpark to perform a statistical analysis of selected data to determine whether reviews from Amazon's Vine program are trustworthy. Ultimately, I determined that Vine reviews may not offer a complete picture of their reliability simply due to the sheer quantity of non-vine reviews to Vine reviews.

## Results
* With the paid reviewers there is a chance that the reviewers maybe biased towards a better review and the opposite maybe truee with the non-paid reviewers or they could be more honest.
* The fact that reviews are weighted by having more recent reviews affect more could be affected by things that are trending and not necessarily better or useful. It could also bne affected by scripts or bots just to make someone some more money. 
* The fact that the products are given to reviewers for free could affect reviews because it could be something they wouldn't maybe pay for but now that they have it they like it for the bang for the buck

# Summary
Scraping through this data with a local machine could take hours or longer. Being able to look at average reviews and doing so quickly is a great way to to understand if this would truly be a product you'd like or are interested in.
