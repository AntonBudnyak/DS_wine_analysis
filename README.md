# DS_wine_analysis
 Repository for the data science wine analysis and rating prediction
## Context
I was looking for educational wine dataset with understandable features and suitable for creating ML model for my first DS project. I couldn't find anything relevant, so decided to scrap data from Vivino.com

## Content
Data contains 4 files for each winestyle: red, white, rose and sparkling. Also there is a file with wine varieties for further analysis.
Files has 8 columns with quite obvious names, maybe I should add that NumberOfRatings is the number of people who rated this wine.

## Inspiration
Analyzing data presented on Vivino.com, I noticed that there are no bottles that have less than 25 ratings, apparently because the company considers the rating of such wines is not accurate enough. So, I had an idea to perfom ML model for predicting the rating of bottles with a small number of ratings. I realised this idea in my project, public notebook with which I also upload here.

As it turned out, the problem of reviews distribution is exists in many spheres. It consists in the fact that customers are often afraid of choosing a product or service that no one has ever bought before. Due to this, many businesses lose large amounts of money on the unnormal distribution of customers by product. My idea is to create a model for any such business that predicts the rating based on other features, it can help to increase the demand for new, but promising products

## Abstract
From the graphic below you can see main problem of the project. Number of Ratings has the exponential distribution and there a lot of wines, which has low Number of Ratings(at Vivino and in this dataset you can see rating of wines which has more than 25 ratings). There is a real problem for business, because the main reason of Vivino app is to give info about quality of wine to customers, but for huge number of wines there are no rating at all.
My idea is to apply ML methods to predict rating of wines wich has less than 25 ratings.
![alt text](https://github.com/AntonBudnyak/DS_wine_analysis_main/blob/master/g1.png)

