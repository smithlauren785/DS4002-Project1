# DS4002-Project1

## Contents of Repository
This repository contains the files and information related to the first project done by Lauren Smith, Ann Sofo and Reese Quillian in the DS 4002 Project Course. In this project we explored the question: Did Donald Trump’s Twitter language change over the course of his campaign/election year (before, during, after his election)?

## SRC


## DATA

### About the Dataset
The original dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/codebreaker619/donald-trump-tweets-dataset). Published in 2021, the csv file provides daily tweet data from Donal Trump’s twitter account from May 2009 (when it was created) until January 8 2021 (when his account was blocked). The dataset provided the text, number of favorites and retweets, whether it was deleted, and the date shown in tweets_original.csv. In total we added 8 features, with 7 to identify whether specific words and phrases from our hypothesis were present, and one to identify the election period in which the tweet was posted shown in tweets_new.csv. 


### Data Dictionary

| Variable Name  | Description  |
|---|---|
| text  | The content of the tweet made  |
| favorites  | Number of likes tweet has  |
| retweets  | Number of times tweet was retweeted  |
|  date | Date of the tweet  |
| isDeleted  | Binary variable showing whether a tweet has been deleted (0 = No, 1 = Yes)  |
| election_period  | Labels whether tweet was posted pre,post, or during the 2020 election; Pre: Before June 16th, 2015, During: June 16th, 2015 - November 8th, 2016, After: After November 8th, 2016 |
|  wall, fake_news, media, democrat, great, trump | Binary variables labeling whether these words are present in the tweet (0 = No, 1 = Yes)  |
| contains_word  | Binary variable labeling whether any of the targeted words are mentioned in the tweet (0 = No, 1 = Yes)  |

## FIGURES

## REFERENCES



