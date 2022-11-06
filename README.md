# Youtube-Data-Analysis

For this project, the objective is to analyze data provided by Youtube API and visualize key metrics and do sentiment analysis on comments data. 

Models used for this project include a differt types of regression: Logistic Regression

## 🔎 Backround

**About Data**

Ken Jee is a data scientist and a youtuber who is working in the data science industry from the last 5 years. He has held data science positions in companies ranging from startups to fortune 100 organizations. He transitioned into data science from a business and consulting background. When he was first starting out on my data science journey he was extremely lost; there were very few resources for him to learn about this field from. He decided to start making YouTube videos to share his experiences and to hopefully help others get break into the data science and sports analytics fields.

In this project Ken has provided his YouTube channel data directly from the YouTube API as his first community project. There are 4 files.

**1. Aggregated Metrics By Video** - This has all the topline metrics from my channel from its start (around 2015 to Jan 22 2022). I didn't post my first video until around

**2. Aggregated Metrics By Video with Country and Subscriber Status** - This has the same data as aggregated metrics by video, but it includes dimensions for which country people are viewing from and if the viewers are subscribed to the channel or not.

**3. Video Performance Over Time** - This has the daily data from each of my videos.

**4.  All Comments** - This is all of my comment data gathered from the YouTube API. I have anonymized the users so don't worry about your name showing up!

## 📈 EDA

### Number of Publishes videos by Year

![plot1](https://github.com/deepdk/Youtube-Data-Analysis/blob/main/Plots/plot%201.png)

In 2020 Ken published 113 videos, while this dropped to 47 in 2021. **Cororna Imapact**

### Top 10 Videos by Views and Likes

![image](https://user-images.githubusercontent.com/31981663/200156043-beb3c0f9-507a-41a7-bb05-467fc69842c6.png)

![image](https://user-images.githubusercontent.com/31981663/200156118-c0f855be-a92f-441b-91c2-43ce9e28cb85.png)

The video **How I would Learn Data Science (if I Had to Start Over)** is by far the most Viewed video of the channel and has also close to ~ 47k likes.

### Total Views by Country

![image](https://user-images.githubusercontent.com/31981663/200156194-278bf4f3-5b1a-4206-9ac5-3854191c7b3c.png)

As we can see from the map it is obvious that the vast majority of Kens YouTube channel views, comes from

- United States of America (1.354.450)
- India (1.155.510)

### Channel Views by Date

![image](https://user-images.githubusercontent.com/31981663/200156258-d0905988-0cc6-404d-a62d-c3fef6193341.png)

### Word Cloud of Comments

![image](https://user-images.githubusercontent.com/31981663/200156590-87ffdda1-8f8b-43e3-bcd4-675fb1e2c800.png)

- First of all, one of the most common words is -Great- and I can also see -good- job, -awesome- etc.,

- A lot of the viewers seem to also talk about getting started, thus we can assume that most of the viewers are beginners trying to understand how they can get started, which explains also the popularity of the -Getting Started / Learning paths- kind of videos!!! A lot of comments seem to also be towards questioning or talking about a degree and/or a masters degree in particular to get going!

- Most of the comments seem to also be concerned about how to get a job, start a career and gain experience in the fields of data science.

- Seems like viewers are mostly talking about mainly Python and SQL regarding hard skills.

- Kaggle is also fairly discussed in the comments, so lets see how many will participate in the project.

## ⚒️ Model

**Logistic Regression Model** is used for predicting positive and negative comments.

**Accuracy Score on training data - 0.9774169921875**

**Accuracy score on test data - 0.89697265625**

### Confusion Matrix

![image](https://user-images.githubusercontent.com/31981663/200156935-87fb1acf-5019-47f3-a6c5-d3f556f5c1e1.png)

**F1 Socre - 0.8755930252543326**

## Conclusion

- As many people are taking interest in the field of Data Science Gettting Started Videos are in demand.

- Doing some collaborations with other YouTubers / Content Creators boots the views and subscribers. Data Science community and audience seems to be growing significantly and the audience is growing fast as people become even more interested in the field of Data Science every year. However, the audience seems to be diluted in a large degree. Thus, by collaborating and especially doing a “live” maybe on Friday a lot more individuals discover your channel, which seems to drive them to further explore your older content, leading them to subscribe.





