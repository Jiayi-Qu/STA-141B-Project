## Yelp Data Analysis ##
## Introduction
User reviews are an important part of web services such as Amazon and Yelp, where users can post their experience and opinions about about businesses, products or services through reviews consisting of text and a numeric star rating, usually out of 5.  These reviews and ratings will give other Yelp users advice to evaluate a business, a product or a service and make a choice. On famous websites like Yelp, many businesses receive hundreds of reviews, making it impossible for readers to read all of them. Normally, readers tend to look at the average star ratings only and ignore the text content. While ratings are useful to convey the overall experience, they do not express the specific context which led a reviewer to that experience. In particular, several questions may be asked if we only pay attention to the star ratings: Why exactly did this customer give the restaurant 3/5 stars? What aspect did this customer




Yelp data challenge is a competition held by Yelp to encourage students to come up with innovative insights of their data. In this way, Yelp will released The Yelp dataset released for 2017 winter challenge contains information for 144 thousand businesses. This dataset has  4.1 million reviews for these business, 1 million users and 125 thousand check-in sets. 

In particular, several questions
may be asked: why exactly did this reviewer give the
restaurant 3/5 stars? In addition to the quality of
food, variety, size and service time, what other features
of the restaurant did the user implicitly consider,
and what was the relative importance given to each of
them? How does this relationship change if we consider
a different user’s rating and text review?

## Goal
- Explore the relation between the user behaviors(rating values and reviews) and business attributes. 
- Predict the user’s rating stars given the reviews they left by application of machine learning.

## Methodology 
- Natural language processing
- Data visualization 
- Geographical data analysis
- (Possible) Multi-class classification (logistic regression, KNN classification) to build predictive model 

## Data wrangling
The first thing we noticed was that the huge size of the data made difficulty in loading. In order to extract the data, we load the dataset into a Jupyter Notebook running on an Amazon Web Service(AWS) spot instance.

## Data Visulization

## Data Analysis

You can use the [editor on GitHub](https://github.com/Jiayi-Qu/STA-141B-Project/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
#
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Jiayi-Qu/STA-141B-Project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
