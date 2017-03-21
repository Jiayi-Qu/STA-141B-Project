## Yelp Data Analysis ##
## Introduction
User reviews are an important part of web services such as Amazon and Yelp, where users can post their experience and opinions about about businesses, products or services through reviews consisting of text and a numeric star rating, usually out of 5.  These reviews and ratings will give other Yelp users advice to evaluate a business, a product or a service and make a choice. On famous websites like Yelp, many businesses receive hundreds of reviews, making it impossible for readers to read all of them. Normally, readers tend to look at the average star ratings only and ignore the text content. While ratings are useful to convey the overall experience, they do not express the specific context which led a reviewer to that experience. In particular, several questions may be asked if we only pay attention to the star ratings: Why exactly did this customer give the restaurant 3/5 stars? What aspect did this customer not satisfy with, the quality of food, waiting time or other consideration?  In this report, we firstly visualize the Yelp dateset of its review system to explore the potential relation between several attributes, then provide suggestions to business owners based on our findings and lastly we classify the star ratings based on users’ reviews to build a prediction model.

##  Data Description
Yelp runs a data challenge every year in which it invites people to explore its real-world datasets for innovative insights. We use the dataset provided by Yelp Challenge 2017 for our data analysis purpose.The dataset includes data from 11 major cities, that is, Pittsburgh, Charlotte, Urbana-Champaign, Phoenix, Las Vegas, Madison and Cleveland in U.S., Montreal and Waterloo in Canada, Karlsruhe in Germany and Edinburgh in U.K. and contains information about 4,100,000 text reviews, 144,000 businesses, 1,100,000 bussiness attributes, 947,000 tips by 1,000,000 users and aggregated check-in sets for each of the 125,000 businesses. Concretely, the dataset consists of five files, one for each object type: business, review, user , check-in and tip. To access this huge dataset, we lauched an AWS EC2 Spot instance to process the dataset(4 million reviews).

## Methodology 
In our project, our work is divided into two part, data visualization and data analysis, using different methodology. In addition, we use Natural Language Processing throughout our project. 

1. Data visulization
- Barplot, Line chart
- Mapping
- Wordcloud
2. Data analysis
- Multi-class classification (SVC, Multinomial Naive Bayes)

For data analsis, we use multi-class classification in Machine Learning where the class lables are the star ratings out of 5. We combine the unigrams feature extraction with 2 supervised learning algorithms, Multinomial Naive Bayes and linear support vector classification(SVC) to build our prediction models.

## Data Visulization

## Data Analysis

![](https://github.com/Jiayi-Qu/STA-141B-Project/blob/master/Picture1.png)
