# Title
Prediction in an Era of Unpredictability 

# Abstract
Recent geopolitical events such as the election of Trump and Brexit have, to say the least, shocked the popular opinion around the globe. Media outlets, political experts, advisors, and data scientists have all failed to come close to predicting the outcome of such events. In hindsight, however, the pieces are obvious to connect. Our goal is to analyze these major past events on the basis of common ideas and popular opinion and see how the former squashed the latter. Using these learnings, we want to try and improve our chances of predicting future events such as the current state of Catalonia. We also want to study the variables which are similar and different in each geopolitical landscape - standard of living, level of education, social media presence, type of government. Are there specific factors which largely shape such seemingly sudden political ‘bursts’ and their outcomes or is it solely the product of erratic human behavior? In this project, we will focus on the Catalan independence movement while analyzing and learning from Brexit and the election of Trump.

# Research questions
To better dissect the data and extract insights, we explore the following questions:
1. Which socio-economic factors have the biggest impact, if any, in building or altering popular opinion?
   * Standard and Quality of Education (Wikidata, Educational databases)
   * Income and Inequality Levels (Wikidata)
2. How does media through newspapers and social networks influence these events through information or misinformation?
    * Newspaper (Corpus Data)
    * Social Media (Twitter)
3. What is the influence of the political system in place?
    *Political system
    * Rate of Abstention (Wikidata)
    * Demonstrations covered in media (Corpus Data)
4. How far in time could we have traced the roots of such events? (Wikidata, Newspapers)


# Dataset

* News On the Web    https://www.corpusdata.org/intro.asp
* Wikidata    https://www.wikidata.org/wiki/Wikidata:Main_Page
* Freebase    https://developers.google.com/freebase/
*Twitter?
* Other

Data Constraints:
To study Brexit, US election and Catalonian independence we need to make sure that
   * We can have access to media information in english, spanish or catalan
   * We can access data recent enough. 
The News On the Web data set offers the  NOW data set ((Currently) 5.26 billion words | 6,000,000 texts | web pages | 20 different countries | Growing by 4-5 million words each day.) This data set will be up to date, but it will cover mostly blog articles. The  “Corpus del Español” ( (Web/Dialects): 1.8 billion words | 1,800,000 texts | web pages | ~ 60% blogs | 21 Spanish-speaking countries ). This dataset would be suitable for extended research on Catalonia.  The GloWbE: (1.8 billion words | 1,800,000 texts | web pages | ~ 60% blogs | United States, Great Britain, Australia, India, and 16 other countries) This data set could be used to study Brexit and trump election. The COCA: 440 million words | 190,000 texts | 1990-2012 | evenly divided (~88 million words each) into spoken, fiction, magazine, newspaper, academic) is more structured, but does not offer data after 2012. 


## Feasibility: 
The projects involves a large range of data. Statistical and categorical data will be extracted from Wikidata to enrich our datasets. Then News on the web as well as twitter data will be used to address the media coverage.
* Point 1. will be the easiest to answer because it require only statistical data. 
* Point 2. is perhaps the most difficult, answering it in depth would require sentiment analysis. An alternative way to answer the question would be to determine Term Frequency (TF) –(TF for a term “t” is defined as the count of a term “t” in a document “D”) or Inverse Document Frequency (IDF)  (– IDF for a term is defined as logarithm of ratio of total documents available in the corpus and number of documents containing the term T. ). This could be done on the News On the Web dataset which offers semi-structured data sets with Database, WordLemPoS formats. The frequencies could be linked with a date of publication of the article and the country of publication. Newspapers countries will be determined via wikidata. As Twitter data were not available on the project spreadsheet we have not made assumptions about the processing strategy yet. 
* Point 3- Will analyze the frequency of text objects related to violent demonstrations. In addition general information about political systems will be obtained from Wikidata. 
* Point 4- Will estimate the time points when such events started being conceptualized in newspapers. For example we will trace back in time the text objects:  “Trump president”, “Brexit”, “Catalonia Referendum independence”. We can also imagine following this world over time. Besides, historical background could be extracted from wikidata.  


# A list of internal milestones
Timeplan up until project milestone 2
* Early November: Ideation and start project
* Mid November: Get all the data needed from the websites
* End November : Combine datasets and extract most relevant information
* Mid December: Mid-term checkpoint - examples of visualizations
* Early January: Initial website/poster design
* Mid January: Poster completion
* End January: End of project and final submission of all deliverables

# Questions for TAs
Is the twitter dataset available? If yes which is its format? 
Do we have access to News On the Web without paying? https://www.corpusdata.org/purchase.asp
Is the project too broad? 


