# Rocket-League-Match-Prediction
Contains jupyter notebooks that scrape various websites, assemble a dataset, and attempt to predict Rocket League match outcome via XGBoost and Logistic Regression. You can read my analysis of the dataset on my [blog](https://walker-payne.medium.com/alternative-data-sources-and-informational-advantages-via-web-scraping-and-machine-learning-8da4ab8aecc3)

1) "Ballchasing Scraper 2.ipynb" scrapes a dataset from ballchasing.com. It looks for data on a match-by-match basis - the date the match occured, the names of the two players involved, and the outcome of the match (who won). 
2) "RL Tracker data.ipynb" uses the dataset from the ballchasing.com scraper to then pull additional information about each player - the number of total wins they have, their goal-to-shot ratio, their 1v1 rating (MMR), etc.
3) "RL Tracker EDA and Model Training.ipynb" then explores the dataset, does some feature engineering, and applies various ML technqiues in an attempt to build a model that can predict the winner of a match, before it happens, based on the player statistics.
