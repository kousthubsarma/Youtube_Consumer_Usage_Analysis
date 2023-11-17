# Youtube_Consumer_Usage_Analysis
This tool lets you analyze YouTube usage, such as watching habit, interests, and behavior patterns, to name a few.



Group #2 Milestone 1

Group names: Sri Yadali, Aayaan Amir, Kousthub Sarma, Satya Bonepalli

Option Choice: Option A - Usage of YouTube as a Content Consumer

Data Plan information:
We plan to use the YouTube Trending Video Dataset (updated daily), the Global YouTube Statistics 2023 dataset  and the Youtube Statistics dataset.

Table 1: User_Details
UserID (PK, CHAR (10))
Username VARCHAR2 (15)
Country VARCHAR2 (20)

Table 2: Video
VideoID (PK, CHAR(10))
CategoryID CHAR(10)
Title VARCHAR2(50)
Date DATE
Keyword VARCHAR2(15)
Likes INTEGER
Dislikes	INTEGER
Comments VARCHAR2(50)
Views INTEGER

Table 3: Channel
Name (PK, VARCHAR2 (50))
Type VARCHAR2(20))
Subscribers INTEGER
Views INTEGER
Videos INTEGER
Rank INTEGER
Country CHAR
Region CHAR

Relationships: User -< Video | User -< Channel | Channel -< Video

Teamwork contribution: 

Sri: Brainstormed datasets, wrote datatypes, planned relationships.
Aayaan: Brainstormed datasets, wrote tables, wrote relationships
Kousthub: Focused on data planning and what insights can be derived.
Satya: Worked on the database design and table relationships.



Group #2 Milestone 2

Group names: Sri Yadali, Aayaan Amir, Kousthub Sarma, Satya Bonepalli

Option Choice: Option A - Usage of YouTube as a Content Consumer

Questions to analyze:

1. What genre of videos have the highest number of likes?
2. Which channels are the most popular and how are they measured?
3. Which video category is the most popular in each country/region?
    1. Knowledge from class: This will leverage data aggregation and regional segmentation techniques.
    2. Importance: Video creators can target their content better based on regional preferences.
4. How does the like/dislike ratio vary by video category across different countries?
    1. Knowledge from class: Analyzing ratio metrics and cross-referencing them with categories and regions.
    2. Importance: To understand the audience sentiment for each category in different regions.
5. Which channels have the highest average likes and which ones have the highest average dislikes?
    1. Knowledge from class: Data aggregation on channels to analyze average metrics.
    2. Importance: To spotlight successful channels and identify ones that may require content strategy changes.
6. Which countries/regions contribute the most subscribers for a given channel?
    1. Knowledge from class: Using join operations to combine channel data with regional subscriber data.
    2. Importance: For channels to understand their primary audience and focus their promotional efforts.
7. What are the top 5 keywords associated with the highest viewed videos in each region?
    1. Knowledge from class: Text analysis and extraction of keywords, coupled with sorting algorithms.
    2. Importance: Video creators can understand trending topics in different regions.
8. How does the seasonality affect video views based on video category?
    1. Knowledge from class: Time-series analysis.
    2. Importance: For creators to understand the best time to release specific content.
9. Which new channels (less than a year old) are gaining popularity the fastest in each region?
    1. Knowledge from class: Date operations and growth rate calculations.
    2. Importance: Spot emerging channels and trends.
10. Is there a correlation between video length and the like/dislike ratio?
    1. Knowledge from class: Correlation analysis.
    2. Importance: To help creators find an optimal video length based on audience sentiment.
11. For videos with a high like/dislike ratio, what time of the day are they most frequently posted?
    1. Knowledge from class: Time-series analysis and pattern recognition.
    2. Importance: To strategize the release time of videos.
12. What are the common themes or topics among the top 10% most disliked videos?
    1. Knowledge from class: Text analysis, sentiment analysis.
    2. Importance: To help creators avoid potentially controversial or disliked topics.



Teamwork contribution: 
Sri: Brainstormed and wrote questions
Aayaan: Brainstormed and wrote questions
Kousthub: Brainstormed and wrote questions
Satya: Brainstormed and wrote questions
