# Title
Prediction in an Era of Unpredictability


# Abstract
Recent geopolitical events such as the Election of Trump, Brexit, and Catalonian Independence have, to say the least, shocked the popular opinion around the globe. Media outlets, political experts, advisors, and data scientists have all failed to come close to predicting the outcome of such events. In hindsight, however, some of the pieces are obvious to connect. Our goal is to analyze the given data on the basis of common ideas and popular opinion and see how the former squashed the latter. Any insights can improve our chances of predicting future events such as the current state of Catalonia. Are there specific factors which largely shape such seemingly sudden political ‘bursts’ and their outcomes or is it solely the product of erratic human behavior? In this project, we will focus on learning from the US Presidential Elections of 2016.


# Research questions
To better dissect the data and extract insights, we explore the following questions:
1. How does media through newspapers (both paper and digital) influence these events through information or misinformation?
2. Is it possible to find the political bias (left, right, or center) of newspapers using existing data and data analysis?
3. How far in time could we have traced the roots of such events and opinions using time series?


# Dataset
News On the Web
* https://www.corpusdata.org/intro.asp
* 5.26 billion words
* 6,000,000 texts and web pages
* 20 different countries
* Growing by 4-5 million words per day


# Feasibility: 
The project involves a large amount of data. Statistical and categorical data will be extracted from Wikipedia to enrich our datasets. Then, the News On the Web dataset will be used to address the media coverage.
* Point 1. This is perhaps the most difficult as answering it in depth would require sentiment analysis. An alternative way to answer the question would be to determine Term Frequency (TF, where TF for a term 't' is defined as the count of a term 't' in a document 'D') and Inverse Document Frequency (IDF, where IDF for a term is defined as logarithm of ratio of total documents available in the corpus and number of documents containing the term 'T'). This could be done on the News On the Web dataset which offers semi-structured data sets with Database, WordLemPoS formats. The frequencies could be linked with a date of publication of the article and the country of publication.
* Point 2. We will perform machine learning using the FastText library and/or LSTM Networks. The training set for our is gathered using a few existing crowdsourced labels for newspapers. Then we try to predict the biases of the test set.
* Point 3. We will estimate the time points when such events and opinions started being conceptualized in newspapers. For example, we will trace back in time the text objects: "Trump", "Clinton", and other keywords. 


# Milestones and Expected Timeline
* Mid November: Ideation and start project
* End November: Get all the data needed from the websites
* Mid December: Combine datasets and extract most relevant information
* End December: Website Data Story
* Mid January: Poster completion
* End January: End of project and final submission of all deliverables



