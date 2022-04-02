---
title: "Data Science, What?"
categories:
  - Data Science
tags:
  - Intro
  - Data Science
  - What

last_modified_at: 2018-02-05T16:19:55-05:00
---

![image-center]({{ '/images/p1I1.jpg' | absolute_url }}){: .align-center}

*Data Science* is an inter-disciplinary field which is used to gain insights into data through computation, statistics and visualization. Inter-disciplinary as in,

The stuff present in the background are the popular softwares and frameworks use to carry out different tasks. Tasks such as? It turns out that, the entire process of gaining insights from the data comprises of several smaller sub tasks such as (Detailed Info in the respective articles):

## Ask an interesting question

Here the question refers the task which you want to achieve in the end. It could be either be prediction or estimation of a variable depending on the past trends, it could also be a particular business question which you want to find an answer of like consumer resoponse for a particular product, grouping of consumers for different products etc.

## Get the Data

In order to derive insigts, you would certainly need the data in the first place! Well, you yourself might be collecting the data so that you would use it now. It may also be the case that you want to use the data collected by others and in that scenario you may scrape the data either from web sites, APIs, online repositories etc. While getting the data you also need have to take care about how the data is sampled, or if there are any privacy issues which you might unintentionally violate. Also you need to take care about the relevance of the data you are using. After getting the data you may also need to clean the data. Cleaning as in if there are partially filled entries you may want to remove them. If the datatypes in the data are inconsistent you'd correct it. 

## Exploratory Data Analysis

The most important task among all the tasks! Well EDA is getting all about getting a flavor of the data which you'd be using. EDA involves usage of visualization techniques in order to find out any anomalies or patterns in the data. You can do so by checking the different statistical measures such as mean, std, median etc. Certaing modeling techniques (to be discussed afterwards) also involve removal of highly correlated features (in other words those features which significantly depend on each other). The removal of correlated features and also the selection of relevant features to be used for modeling purposes.

## Model the data

This is the task about which you may hear in various articles as "Machine Learning", "Neural Networks", "Regression", "Classifiers" etc. Now, Machine Learning is a sub-field of CS which comprises of algorithms which improve their performance with data. Here the performance may refer to predicting a dependent variable given the values of several independent variables, grouping the data based by finding certain common features, take a decision etc. Such algorithms are known as learning algorithms, this is because in a way the algorithm learns the relation between the dependent and independent variables. These learning algorithms when trained with data. The learning algorithms require data to update their hypothesis relation in order to make better predictions. This is known as the training of the model.

## Communicate and Visualize the results

After you are done with the model forming part, you would certainly want to use it for the prediction of some other stuff. We need to make certain sanity checks whether the predictions made are sound enough or not. In this task you'd prefer to use certain visualization tools. So we use visualizations firstly for EDA and secondy for communicating the results.

Well turns out that there's so much buzz in the media about this, and one of the reasons for this is,

> Data Scientist is the sexiest jobs of the 21st Century.
>
> <footer><strong>Harvard Business Review</strong></footer>

You can check this [Harvard Business Review](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) article. Is it really the case? 

> I am a data scientist…
I don’t find my job sexy.
I am 40% a vacuum, another 40% a janitor.
And the last 20%… A fortune-teller.
>
> <footer><strong>Jingles (Hong jing)</strong></footer>

You can check this article as well by [Jingles (Hong jing)](https://towardsdatascience.com/data-scientist-the-dirtiest-job-of-the-21st-century-7f0c8215e845). Well, there are opinions but, I really find it cool!

Finally the roadmap!

![image-center]({{ '/images/DSMap.png' | absolute_url }}){: .align-center}

## References:

1. [CS109 Data Science, Harvard University](https://cs109.github.io/2015/index.html "Lectures")
