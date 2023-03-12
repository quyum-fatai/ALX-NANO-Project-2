# Project: Wrangling and Analyze Data - WeRateDogs
## By Quyum Fatai

## Project Overview
> The aim of the project was to make a wrangle effort on the dataset of WeRateDogs, a twitter handle that rates dogs based on some specific criteria. Data was gathered from
the twitter handle and twitter API. After a thorough analysis through data assessment and cleaning, insights were made from the dataset

![dog-rates-social](https://user-images.githubusercontent.com/127361595/224523557-2857d2b3-e232-408d-8492-a08e4b69be54.jpg)

## Datasets
> Datasets of different formats were gotten from different sources. The datasets include;
- Directly downloaded the WeRateDogs Twitter archive data (twitter_archive_enhanced.csv)
- Use the Requests library to download the tweet image prediction (image_predictions.tsv)
- Use the Tweepy library to query additional data via the Twitter API (tweet_json.txt)

## Installations
- pandas
- NumPy
- requests
- tweepy
- json

## Insights
**_Insight One:_**
It was discovered that about 577 of the dogs in the dataset have no name, the next highest on the list has a
name of 'a' which seems to be pretty unusual as a name and lastly, the third dog happens to be 'Charlie'
with a count of 11

**_Insight Two:_**
It was discovered that dogs with the stage name 'pupper' have the highest number of retweets to the tune of
‘478,883’

**_Insight Three:_**
Furthermore, it was discovered from the analysis that 2016 has the highest number of likes out of the years
present in the dataset

**_Insight Four:_**
The fourth insight that was discovered is that out of all the months in a year, December has the highest
number of likes. This could have been due to the merriments of the season or some other factors. It is
worthy of note that the merriment stated does not absolutely determine the number of likes
