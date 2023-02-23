# DS4002-Project1

## Contents of Repository
This repository contains the files and information related to the first project done by Lauren Smith, Ann Sofo and Reese Quillian in the DS 4002 Project Course. In this project we explored the question: Did Donald Trump’s Twitter language change over the course of his campaign/election year (before, during, after his election)?

## SRC

### Installing/Building Code
Each file in our src folder is an R Markdown document that can be downloaded and opened up in RStudio. Additonally, they can be knitted to HTML upon opening in RStudio to produce a more readable format. 

### Code Usage
In order to successfully run the code chunks in the R Markdown files, a few packages need to be installed. When opening the file in RStudio, a message at the top of the source code will ask you if you would like to install the required packages. Click install. Then run the first code chunk which reads in the required packages. Additonally, download the CSV files in the data folder of the repository and set your working directory to their location. 

There are two R Markdown files with our code for the project: Project_EDA.rmd which demonstrates our data cleaning process and exploratory data analysis and Proj1_ModelBuilding.rmd which shows our model building process. Project_EDA.rmd reads from the tweets.csv file and Proj1_ModelBuilding.rmd reads from the tweets_clean.csv file. 


## DATA

### About the Dataset
The original dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/codebreaker619/donald-trump-tweets-dataset). Published in 2021, the csv file provides daily tweet data from Donald Trump’s twitter account from May 2009 (when it was created) until January 8 2021 (when his account was blocked). The dataset provided the text, number of favorites and retweets, whether it was deleted, retweeted or flagged, the device the tweet was sent from, and the date shown in tweets.csv. In total we added 8 features, with 7 to identify whether specific words and phrases from our hypothesis were present, and one to identify the election period in which the tweet was posted shown in tweets_clean.csv. 


### Data Dictionary

| Variable Name  | Description  |
|---|---|
| text  | The content of the tweet made  |
| isRetweet  | Whether or not a tweet is a retweet (TRUE/FALSE)  |
| isDeleted  | Whether or not a tweet was deleted (TRUE/FALSE)  |
| device  | Device tweet was sent from |
| favorites  | Number of likes tweet has  |
| retweets  | Number of times tweet was retweeted  |
|  date | Date of the tweet  |
| isFlagged  | Whether or not a tweet was flagged (TRUE/FALSE)  |
|  wall, fake_news, media, democrat, great, trump | Binary variables labeling whether these words are present in the tweet (0 = No, 1 = Yes)  |
| contains_word  | Binary variable labeling whether any of the targeted words are mentioned in the tweet (0 = No, 1 = Yes)  |
| TimePeriod  | Labels whether tweet was posted pre or post start of the 2016 election; Pre: Before June 16th, 2015 and After: June 16th, 2015 and after |


## FIGURES

| Figure  | Takeaway  |
|---|---|



## REFERENCES

C.  Van den Rul, “How to generate word clouds in R,” Medium, 20-Oct-2019. [Online]. Available: https://towardsdatascience.com/create-a-word-cloud-with-r-bde3e7422e8a. [Accessed: 22-Feb-2023]. 

Zach, “How to use str_detect() function in R (3 examples),” Statology, 07-Apr-2022. [Online]. Available: https://www.statology.org/str_detect-in-r/. [Accessed: 22-Feb-2023]. 

Wright (2022) Decision Trees. https://github.com/UVADS/DS-3001/blob/main/08_DT_Class/Decision%20Trees.Rmd.


