# CHIsentiment: Exploring Public Sentiments of Chicago Neighborhoods

What is the relationship between the reputation and the characteristics of a neighborhood? In this project I explore this question in the context of Chicago, IL, using social media (Twitter) data and a dataset of socioeconomic data per neighborhood available from the City of Chicago data portal (https://data.cityofchicago.org). For this exploration, a "neighborhood" is defined as one of Chicago's 77 community areas, which are officially recognized by the City of Chicago. I model neighborhood reputation as an index summarizing the sentiment of tweets mentioning a given neighborhood.

I proceed in the following steps:
* Set up (import modules and keys that I'll need along the way)
* Construct dataset
    - Download relevant Twitter data
    - Apply sentiment analysis to tweets
    - Generate neighborhood reputation index scores for each neighborhood
    - Put socioeconomic and Twitter data per neighborhood into one table
* Develop descriptive statistics
* Develop infenrential statistics
* Conclusions
