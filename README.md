# emoji-prediction

## Data Curation

- For our problem statement, we decided to scrape tweets as it is the best open source of conversational messages with emoji data. 
- We created an app on the twitter developer account, and used the app keys to scrape tweets using APIs.
- Due to their strict tweet download quotas, we ran the crawler with regular timeouts. We ended up curating about 400k tweets. 
- We then further filtered tweets that contain 1 of our target 20 emojis. We also chose only those tweets that contain exacly 1 emoji. 
- Finally, we ended up with 365671 tweets. 

## Data pre-processing

- Checkout the dataset_curation.ipynb notebook for all pre-processing steps taken

## Model pre-processing

- Checkout the modeling.ipynb notebook for details concerning how we create the dataset class and prepare input prior to feeding into models. 