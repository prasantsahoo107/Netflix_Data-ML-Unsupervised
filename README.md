# Netflix Movies and TV shows Clustering
To ensure an optimal user experience and prevent subscriber churn, it is essential for Netflix, the world's leading online streaming service provider with over 220 million subscribers as of 2022, to effectively cluster the shows on their platform..

## Table of Content
  * [Problem Statement](#problem-statement)
  * [Objective](#objective)
  * [Dataset](#dataset)
  * [Data Pipeline](#data-pipeline)
  * [Project Structure](#project-structure)
  * [Conclusion](#conclusion)
  
  
## Problem Statement
  The goal of this project is to analyze the Netflix catalog of movies and TV shows, which was sourced from the third-party search engine Flixable, and group them 
  into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider, 
  Netflix, which currently boasts over 220 million subscribers as of 2022-Q2. The dataset, which includes movies and TV shows as of 2019, will be analyzed to uncover 
  new insights and trends in the rapidly growing world of streaming entertainment.
  
## Objective
  The objective of this project is to organize the Netflix shows into distinct clusters, where the shows within a cluster are alike and the shows in different 
  clusters are dissimilar to one another.
  
  
## Dataset
  The dataset used in this project is sourced from Flixable, a third-party Netflix search engine. The data includes information on all movies and TV shows available 
  on   the streaming platform as of 2019, with a total of 7787 records and 12 attributes. Each attribute provides specific information about the movie or TV show. 
  For more information on the dataset, please visit the AlmaBetter website or https://drive.google.com/file/d/1xJGllnE12mAggLuRo8b0oNSshUlG8GvF/view?usp=sharing
  
  
## Data Pipeline
  1. Know Your Data:
       The first step in this project was to examine the various features of the dataset, understand the structure of the data and identify any patterns or trends. 
       We looked at the shape of the data, the data types of each feature, and a statistical summary.
  2. Exploratory Data Analysis:
       We conducted an exploratory analysis of the data to identify patterns and dependencies, and to draw conclusions that would be useful for further processing.
  3. Data Cleaning:
       We checked for duplicated values in the dataset and then addressed any null values and outliers by imputing empty strings and dropping some of the null rows.
  4. Textual Data Preprocessing:
       We used techniques such as stop word removal, punctuation removal, conversion to lowercase, stemming, tokenization, and word vectorization to prepare the 
       textual data for clustering. We also used Principal Component Analysis (PCA) to handle the curse of dimensionality.
  5. Cluster Implementation:
       We used K-Means and Agglomerative Hierarchical clustering algorithms to cluster the movies and determine the optimal number of clusters.
  
  
## Project Structure
```
├── README.md
├── Dataset 
│   ├── [NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv](https://github.com/Navneet2409/netflix-movies-and-tv-shows-clustering/files/10660309/NETFLIX.MOVIES.AND.TV.SHOWS.CLUSTERING.csv)
├── Problem Statement
│
├── Understanding Data
│
├── EDA
│   ├── Numeric & Categoric features
│   ├── Univariate Analysis
│   ├── Bivariate Analysis
│   ├── Multivariate Analysis
├──Data Cleaning
│   ├── Duplicated values
│   ├── NaN/Missing values
│   ├── Treating Outlier 
│
├── Textual Data Preprocessing
│   ├── Clustering Attributes
|   ├── Removing Stopwords
│
├── Model Building
|   ├── Clustering Implemention
|       ├── K-Means Clustering
|       ├── Agglomerative Hierarchical Clustering
|           ├── Dendogram
```


## Conclusion
```
-In this project, we tackled a text clustering problem in which we had to categorize and group Netflix shows into specific clusters in such a way that shows in the same cluster are similar to one another and shows in different clusters are not.

-From elbow and sillhoute score ,optimal of 26 clusters formed , K Means is best for identification than Hierarchical as the evaluation metrics also indicates the same.in kmean cluster 0 has the highest number of datapoints and evnly distributed for other cluster

-Netflix has 5372 movies and 2398 TV shows, there are more number movies on Netflix than TV shows.

-TV-MA has the highest number of ratings for tv shows i,e adult ratings

-Highest number of movies released in 2017 and 2018 highest number of movies released in 2020 The number of movies on Netflix is growing significantly faster than the number of TV shows. We saw a huge increase in the number of movies and television episodes after 2015. There is a significant drop in the number of movies and television episodes produced after 2020. It appears that Netflix has focused more attention on increasing Movie content than TV Shows. Movies have increased much more dramatically than TV shows

-The most content is added to Netflix from october to january

-Documentaries are the top most genre in netflix which is fllowed by standup comedy and Drams and international movies

-Kids tv is the top most TV show genre in netflix

-Most of the movies have duration of between 50 to 150
 Highest number of tv_shows consistig of single season
 Those movies that have a rating of NC-17 have the longest average duration.
 When it comes to movies having a TV-Y rating, they have the shortest runtime on average

-Unitated states has the highest number of content on the netflix ,followed by india

-India has highest number of movies in netflix

-30% movies released on Netflix. 70% movies added on Netflix were released earlier by different mode
    ```
