# Analysis of Tweets from WeRateDogs (@dogrates)
## by Ezekiel Okato


## Project
This project was submitted as part of **Udacity's Data Analyst Nano Degree Programme**. It covers the Wrangling phase of the data from WeRateDogs which involves gathering, assessing, and cleaning data. The data used for this project was gathered using 3 methods i.e.: manually downloading available data, performing a Request to call the URL that hosts the data, and querying Twitter API for additional data. The data was then assessed for quality and tidiness issues. Finally, the data was cleaned and respective datasets were merged and stored for EDA and Data Visualization.


## Summary
This project encompassed all the steps of data wrangling of 3 datasets in order to obtain a master dataset for final exploratory analysis.

### Gathering
For the project, 3 datasets were required in order to successfully accomplish the analysis.

* Dataset 1 - Enhanced Twitter Archive
This dataset was provided by Udacity to be downloaded manually which contains the basic data for 5,000+ Tweets. Udacity enhanced this original dataset by extracting dog ratings, dog names, and dog stage from each Tweet's text data. The original dataset was filtered to produce 2,356 rows of data which include only the Tweets that appear to mention dog ratings during enhancement.

* Dataset 2 - Image Predictions
Udacity provided the **image_predictions.tsv** which is hosted on Udacity's servers and was downloaded programmatically using the Requests library from a URL that was provided.

* Dataset 3 - Additional Tweet Data
The retweet and favourite counts of each tweet which were omitted during the process of enhancing the Twitter archive were gathered by querying Twitter's API with Python's Tweepy library. This JSON-formatted data was dumped to a `.txt` file.

### Assessing Data

The three datasets gathered were assessed for quality issues which deal with the content of the data and tidiness issues which affect the structure of the data. Only necessary observations of issues pertaining to cleaning of data were documented. During assessment, a copy of each dataset was created and assessed. 

### Cleaning, Merging and Storing Data
After cleaning, the datasets were merged and then stored as a separate file for EDA and Data Visualization.

# We_Rate_Dogs_Tweets_Analysis
