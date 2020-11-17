# Sentiment Analysis and Visualization using an US-election dataset for the 2020 Election

[![Check Report](https://github.com/cybertraining-dsc/fa20-523-316/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-316/actions)

- [ ] please use proper refernce citations, they must be cited in text not cited: 

[^1] [^2]

Sudheer Alluri, Indiana University, fa20-523-316, ngsudheer@gmail.com

Vishwanadham Mandala, Indiana University, fa20-523-325, vishwandh.mandala@gmail.com

[Edit](https://github.com/cybertraining-dsc/fa20-523-316/blob/master/project/project.md)

{{% pageinfo %}}

## Abstract

Sentiment analysis is an evaluation of the opinion of the speaker, writer or other subject with regard to some topic.We are going to use US-elections dataset and combining the tweets of people opninon for leading presidential candidates. We have various datasets from kallage and combining tweets and NY times datasets, by combining all data predication will be dervied.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** sentiment,  US-election


## 1. Introduction

For our final project, we will be focusing on the upcoming U.S. presidential elections. More specifically, we will be attempting to predict the winner of 2020’s u.S. elections.As many people across the world know, the United States Presidential elections is a very grand and important political event for the people and government of the United States of America. Not only that, the results of this election will impact the world as a whole. This year, there were many candidates. However, the election boiled down to the Democrat candidate, Joe Biden, fighting against the current Republican President of the United States of America, Donald J. Trump. There are many problems that we can run into while predicting the winner. We plan to use a US-elections dataset to predict the votes each contestant will attain, by area. With growing data, the prediction will be changing constantly. We are making the difference by selecting the latest dataset available and previous election data to predict the number of votes each contestant will get to the closest figure. A feature we are introducing to enhance the quality is predicting various area types like counties, towns, and/or big cities.
One might argue that these kinds of predictions will only be helping organizations and not individuals. We assure you that this project will be helping the general public in many ways. The most evident being, an individual knowing which contestant his/her community or the general public around him/her prefer. This project is strictly statistical and does not have a goal to sway the elections in any way or to pressure an individual into picking a candidate. Overall, this is just a small step towards a future that might hold an environment where the next president of the United States of America could be accurately guessed based on previous data and innovative Big Data Technologies.

## 2. DataSets

We will be going to use the dataset, <https://www.kaggle.com/tunguz/us-elections-dataset> [citation missing], and we will create the filets based on location. If needed, we may download Twitter data from posts on and by Donald Trump, Joe Biden, and their associates. Which leads us to our objective for the project, based on the data we collected, we should be able to predict the winner of the 2020 United States of America’s presidential elections.

All of the data will be location-based and if required we will download realtime campaigning and debate analysis data, giving us a live and updated prediction every time increment. To strengthen the prediction, even more, we may reuse some code from the 2016 election’s analysis, however, our main focus will be using the latest data we readily acquire during the time leading up to the 2020 election.
In conclusion, to make our predictions as realistic and as strong as we can get, we will be going to choose multiple data sets to integrate between the previous election and twitter data to predict the number of votes each candidate will acquire. Therefore, we will be predicting the winner of the 2020 presidential elections.

## 3. Methodology/Process

Our project has two main sections of data sets in it. The first and primary one containing candidate information and previous presidential election data and the second containing twitter data. We believed the second needed more time because the first dataset contained straightforward facts while the twitter dataset is more susceptible to different perspectives and viewpoints.
In this project we are analyzing twitter data of key presidential candidates and other key supporters.We gathered the data from kaggle datasets. Data is mainly divided into 3 sub categories. Tweets made by key personnel.Twitter profiles of the two candidates(all info including followers, following, number of tweets,etc.).The final category involves graphs for visualization purposes.A problem with twitter data is the fact that it is huge. We are using google drive and with it comes the problem of storage. To combat this we are only using 4 twitter data sets. The datasets of Donald J. Trump, Joe Biden, Kamala Harris, and Mike Pence. We also downloaded these data sets to use them locally.There are mainly 3 types of formats used in everyday twitter use: images, text, and video. Only text will be used in this project because the others are not useful for the purpose of the
experiment. Our project mostly uses twitter data as support to the primary dataset.It is there to strengthen the already predicted result. The reason why we cannot make the twitter data set our primary data set is because the data(tweets) are mostly opinion based with only some exceptions. So we cannot predict with the twitter data,however, it
can be used to show public support which will be vital in supporting the prediction derived from the primary data set.So, we found many twitter data sets on keggle and used certain parts from each to make our final four. The difference between the background sets and our final four datasets is the fact that their primary dataset was the twitter data while we used twitter data as our secondary dataset. We realized that twitter data is best used as secondary data that supports the primary dataset, which is more fact based.We can use three of the four OSoMe tools available: trends, networking, and maps. Trends and networking can be combined to find a group that involves every user that is taking part in the elections in some way. Mapping can show these users and their location. Giving us the area based result that we seek. However this method is already a part of our project .Due to the fact that all this data is in keggle in a wider array. Which gave us the option to condense into four large data sets.


Have used the python lib pandas to get tweets and clean it in required format. Used libary seaborn to represent the details in graph and taken the screenshots from it.

We will collect election data and twitter information and integrate both to predict the results. A lot of twitter or dataset data will be trimmed and parsed to build the model. We will calculate
Our data-gathering and preparation methodology is composed of the following steps:

* Use the latest election dataset-2020, we will be creating the model.
 
* Data cleaning and extraction.
* We will try to download the latest data from twitter and campaigning.

## 4. Development of Models

  Candident info
    Age of Democratic primaries candidates
    For some candidates it is very important to mention Women, but not for all. Added Country for reference.
    Where are the Democratic Candidates coming from
    Twitter Engagement, likes and retweets¶
    Buzzwords for each candidate
    
    Pandas: 
    Used to extract the data and clean the tweets.
    Seaboarn and matlab, used to represent the status of elections in the graphs.

## 5. Technologies used

Python, Jupyter notebook or collab, Pandas, Scikit-learn

## 6. Results

After all the data was collected, we ran the data analysis and arrived at these results. The analysis’ prediction favored Joe Biden to win this year’s election. However, President Trump was close behind. The predicted race included a very tight race, ending with Joe Biden breaking through. The actual presidential race this November seemed to be following the predicted trend, with Joe Biden taking a lead at the start and President Trump catching up by the first day’s end. The race continued to be tight for a couple of days, matching the general trend of the prediction. However, on November 7th, Biden broke through the stalemate and secured the elections. The prediction was close for most of the race, but the trend broke when Joe Biden won by a convincing lead.

![Predicted results of US Elections 2020](https://raw.github.com/cybertraining-dsc/fa20-523-316/main/project/images/Electionresults.png)



**Figure 1:** Predicted results of US Elections 2020

![Liked Tweets of US Elections 2020](https://raw.github.com/cybertraining-dsc/fa20-523-316/main/project/images/likedtweets.png)

**Figure 2:** Liked Tweets of US Elections 2020

Reference image: <https://www.kaggle.com/radustoicescu/2020-united-states-presidential-election/notebooks> and edited it form our program.

Below is the example of extracing tweets and forming into graph to represent the data.
Among the most frequent words in tweets dedicated to Donald Trump (excluding candidates' proper nouns) occur both popular election words: "vote", "election", "president","people", "Election Day", etc., and specific, like "MAGA" (Trump's tagline "Make America Great Again") or "die" (a word with negative sense). Specific words of tweets dedicated to Joe Biden: "Kamala Harris" (Vice President-elect of the United States), "BidenHarris", "win" (a word that is more frequent regarding Joe Biden than Donald Trump). Let's look at Bi and Tri n-grams of words.
    
![Words used in  US Elections 2020](https://raw.github.com/cybertraining-dsc/fa20-523-316/main/project/images/__results___53_0.png)

**Figure 3:** Words used in US Elections 2020
    
Reference image: <https://www.kaggle.com/radustoicescu/2020-united-states-presidential-election/notebooks> 



## 7.Conclusion

So, we've taken a quick look at the sentiment of tweets. There are a lot of analysis variants. It looks great to study the tweets by each twitter account, for instance, but these features have a lot of NaN values, and therefore don't cover the actual situation. Based on the analysis from the twitter the predicted winner is projected.The sentiment analysis was performed only on data that had geo-data originating from the "United States of America" to try to ascertain the sentiment in each respective dataset and therefore each presidential candidate.

## 8. Plan for the rest of the Semseter

October 26:
- Furthur looking into new datasets and getting new twitter data. 
- Brainstrom ideas for future engineering and build features
- update the report.

November 2:
- Working on creating function to download the content. Remove the spaces in the project.

November 9:
Completed major part of the notebook, uploaded only neccessary files and modified the code.

November 16:
- Theoretical results were derived and compared with actual results, posted at sub section 6.



## 9. Refernces

[^1]:Taken election dataset <https://www.kaggle.com/kerneler/starter-2020-united-states-e6a4facf-a>

