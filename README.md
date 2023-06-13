
# SDS podcast NLP analysis

This project was carried out 

### Executive Summary

Podcasts are more popular than ever in [United States](https://www.statista.com/chart/10713/podcast-listeners-in-the-united-states/) and its future looks very promising. With ease of access and extensive pool of content available on [different genres](https://www.buzzsprout.com/blog/podcast-statistics), there are over [82 million people listened to podcasts in 2021](https://www.statista.com/topics/3170/podcasting/#topicOverview) and these numbers are estimated to rise even further, reaching over 100 million listeners in 2024. 

There are number of Data Science podcasts featured on different platforms. The goal of this project was to analyze Data Science Podcast content. Transcripts for over 680 episodes of [Super Data Science](https://www.superdatascience.com/podcast) podcast. Different NLP analysis tools were used to extract interesting information and patterns from this pool of fascinating conversation. This project involved web scraping, understanding data, data preprocessing, exploratory data analysis (EDA), sentiment analysis, keyword extraction and topic modeling.

### Motivation

Like many people, I find it enjoyable to listen to music or podcast while cooking, exercising or cleaning house. It helps me to be focused and make the process more fun. A few days ago, when I was actively searching for my project topic and I came across this article: https://blog.deepgram.com/parse-podcasts-with-python-deepgram-asr-text-analysis/. I had the idea to implement similar concept and analysis to one of my personal favorite podcast ‘Super Data Science’. This podcast was launched in 2016 and still active with over 680 episodes and 7.61K subscribers on YouTube alone. These episodes covers a wide range of topics related to data science including machine learning algorithms, deep learning, NLP, computer vision, big data technologies, data visualization, data engineering, artificial intelligence, business application of data science, career tips and many more. In addition, these episodes follow consistent format of conversation between host and one other guest. These guests are experts in field of data science, academics, and many of them are entrepreneurs and industry leaders. They share their experience and insights on various aspects of data science and talk about current and future scenarios. 
This was a very good data set to perform NLP analysis to understand evolution of topics, ideas, and thoughts in field of data science in past 6 years. In addition, analysis helped in understanding sentiments associated with different topics specially AI technology and its tools. I believe like me other Data Scientists will be curious too.

### Data Sources

Transcripts and other information was web scraped from SuperDataScience [website](https://www.superdatascience.com/podcast)  .

### Data Question

Ultimately, I was curious to uncover patterns on podcast content based on EDA and NLP analysis using python libraries. I had various questions in my mind such as
1.	Most common topic discussed.
2.	What are the different topics discussed and they have evolved over the time? 
3.	What are the guest sentiments associated with different topics? 

#### Techniques used in this project were

* [Sentiment Analysis: TextBlob](https://textblob.readthedocs.io/en/dev/)
* [Keyword Extraction: Yake](https://github.com/LIAAD/yake)
* [Topic Modeling: BERTopic](https://maartengr.github.io/BERTopic/index.html)


### Insights

* Text cleaning was really challenging due to conversational nature of the text and dissimilarity between structure of episode transcripts 
* Over the years, increase in episodes featured in Artificial Intelligence category
* Negative sentiments per episode are higher in Artificial intelligence, Machine learning and Deep learning categories as compared to others categories. Each dialogue in episode needs to be   individually evaluated for sentiments associated with a technology as sentiments can be influenced by speaker background
* Unique keywords extracted fairly represent the categories episodes are classified in.  Overlap between episode categories complicated the process
* Topic modeling represented text into different topics and how they have evolved over time
