# WatchCustomerReviewNLP

## This README is still under revision, but please refer to the summary below for now

Dataset: 960k watch customer reviews, coutrsey of LaiOffer - datascience bootcamp

Schema: 

    Column             Non-Null Count   Dtype 
    ---  ------             --------------   ----- 
0.   marketplace        960056 non-null  object
1.   customer_id        960056 non-null  int64 
2.   review_id          960056 non-null  object
3.   product_id         960056 non-null  object
4.   product_parent     960056 non-null  int64 
5.   product_title      960054 non-null  object
6.   product_category   960056 non-null  object
7.   star_rating        960056 non-null  int64 
8.   helpful_votes      960056 non-null  int64 
9.   total_votes        960056 non-null  int64 
10.  vine               960056 non-null  object
11.  verified_purchase  960056 non-null  object
12.  review_headline    960049 non-null  object
13.  review_body        960056 non-null  object
14.  review_date        960052 non-null  object
dtypes: int64(5), object(10)

Pipeline:
1. Read data
2. Tokenize and stemming
3. TF-IDF
4. K-means
5. Latent Dirichlet Allocation
