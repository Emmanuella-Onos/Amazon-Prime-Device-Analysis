# Amazon-Prime-Device-Analysis
Analyzes how the log in device of 2,500 fictional subscribers affect usage frequency and rating
----------
## Overview
Amazon Prime is a video streaming platform that offers subscription-based viewing options for its customers. The project is to analyze how the device subscribers log in to the platform affect their usage frequency and ratings. It consisted of 2,500 fictional Amazon Prime video subscribers.

## Dataset
The dataset consisted of 1 table with 12 columns: customer id, customer name, date of birth, devices, usage frequency, location, ratings, renewal status, customer support, genre, payment, comments.

## Data Cleaning and Manipulation
Since the business involved devices, usage frequency, and ratings, location, renewal status, genre, payment, and comment columns were removed.
Duplicate values on the customer ID column were removed. To group the ratings, DAX IF function was applied. A new column was added to represent the ratings as 3.0-3.4, 3.5-3.9, 4.0-4.4, 4.5-4.9, and 5. There was no rating below 3.0.

## Data Analysis and Result
![](AmazonPrime(1).jpg)
1.	Most users log in with smartphones and tablets.
2.	Smartphone users are more frequent than any other users while tablet users are less frequent but more regular.
3.	Most smartphone users rate the product between 4.5-4.9. This is the highest number of ratings.

## Recommendation
Seeing that smartphone and tablet users are frequent, regular, and give the highest ratings, focus should be placed on these groups of subscribers while making decisions concerning the platform’s features like video quality, size, and customer support features. 
Also, marketing efforts should focus on these groups.
