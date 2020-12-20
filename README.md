# Ford GoBike System Data Exploration
## Data Overview
This data set includes information about individual rides made in a bike-sharing system covering the `greater San Francisco Bay` area during **February 2019**.<br>
`Data Source`: [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)<br>
For more data or any exta information go to [bikeshare.com](https://www.bikeshare.com/data/)

## Wrangling
The raw data contains NaN records also some numbers of outliers records needed to cleaned.
So wrangling part take actions to:
* eleminate null records.
* check for duplicates
* eleminate outliers points in data fields.

## Feature Engineering 
Dataset doesn't contain sufficient features to produce persuasive visualization. However, more features can be 
extracted from the primary features for example: `duration_min` `distance_meter` `day` `hour` `age`.

## Exploration
Walking through data features I start with univariate visualiztoin to show distribution of features, Then we can detect the outliers.<br>
Secondy, I moved to bivariate visualiztoin to illustrate some relation between the features themself in order to decide which features relate to 
each other.Finally, Multivariate visulization of features to help us to answer some questions.

## Findings
* most of users' ages at their thirties.
* most of users cycle around 1 km for both costumer and subscriber.
* most of costumers' trips take around 15 mins, subscribers' trips take around 10 mins.
* most of trips start between 4-6 PM or 7-9 AM.
* trips in day have the same pattern for both costumers and subscribers.
* numbers of costumers trips over a week is steady unlike subscribers trips which decreased significantlly during weekends.
* usually costumers trips take more time than subscriber.

## Explantion
* user Charactersitics
* What is the mean age of user? 
* How far do they go?
* How long does the average trip take?
* Which stations are most popular?
* When are most trips taken in terms of time of day?
* What days of the week are most rides taken on?

## Conclusion
>**In conclusion, based on visualization statistics; bike sharing usage among subscribers focuses on going to nearby work and return to home later. costumers usage is less directed to going to work but it is not siginficant to numbers of subscribers.**

