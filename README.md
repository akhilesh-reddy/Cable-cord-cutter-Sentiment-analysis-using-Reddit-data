
## Analysis-of-Cable-cordcutter-phenomenon using text analytics

### Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Algorithms](#algorithms)
* [Approach](#approach)
* [Insights](#insights)

### Introduction
In this project, we have scraped data from Reddit and performed Named entity recognition and topic modelling on the comments to understand public views about moving from cable channels to streaming services

[Cable cord cutter analysis using text analytics.ipynb](https://github.com/akhilesh-reddy/Cable-cord-cutter-lift-and-sentiment-analysis-using-Reddit-data/blob/master/Cable%20cord%20cutter%20analysis%20using%20text%20analytics.ipynb) has the final code.  
[Text Analytics Final Project presentation.pdf](https://github.com/akhilesh-reddy/Cable-cord-cutter-lift-and-sentiment-analysis-using-Reddit-data/blob/master/Text%20Analytics%20Final%20Project%20presentation.pdf) has our final presentation.  
	
### Technologies
Project is created with:
* Python 3.6.5

**Packages**
nltk  
spacy  
gensim  
vader  

**Datasource**
* Data scraped from Reddit
* Reddit API
* Pushshift.io Bigquery database

### Algorithms 
* Latent Dirichlet Allocation  
* Named entity recognition using spacy
* Sentiment analysis

### Approach:
1. Extraction of data from Reddit
2. Performing Named entity recognition analysis to get the various organizations that the people are talking about.  
3. Topic modelling to understand to understand the primary and common concerns that cordcutters are expressing in their comments  
4. Sentiment analysis to understand customer's sentiment towards cable companies

### Insights: 
* We see that primarliy cord cutters voiced their opinion about user experience, net neutrality, sports packages and traditional cable experience in their comments  
* Niche products – FuboTV – are associated more with product related topics as opposed to general interest topics  
* 
