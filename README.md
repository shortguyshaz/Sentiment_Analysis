# Sentiment_Analysis

Created a neural network to analyse the sentiments of reviews given to clothing items on ecommerce websites. The reviews are classified into 3 categories: positive, negative, and neutral

I used this dataset from kaggle to train the network: https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews

This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
Age: Positive Integer variable of the reviewers age.
Title: String variable for the title of the review.
Review Text: String variable for the review body.
Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
Division Name: Categorical name of the product high level division.
Department Name: Categorical name of the product department name.
Class Name: Categorical name of the product class name.

This is the model I used for reference: https://medium.com/towards-artificial-intelligence/sentiment-analysis-opinion-mining-with-python-nlp-tutorial-d1f173ca4e3c
