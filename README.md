![Indian Premier League](https://spiderimg.amarujala.com/assets/images/2018/01/04/750x506/ipl-2018-retention_1515071399.jpeg)

### Exploratory Analysis on IPL Data

EDA is one of the most important aspects of any Data Science project. It easily accounts for 60-70% of work before one goes on to modelling. EDA is basically 'A first glance at the data'. In order to generate a good model from the dataset we first need to understand the data. EDA helps in achieving that. It summarizes data, finds patterns between data points and is often presented via visual methods (diagrams, graphs) for easy understandability.

Real world data is most of the times unstructured and dirty in nature. If we do not perform EDA first and directly feed this data into any machine learning algorithm, then we can be pretty sure that we would not get any desireable result. As it is often said 'Garbage In Garbage Out'. EDA helps in identifying gaps in the data and then filling those gaps appropriately. 

The primary objective of any EDA process is to analyse the underlying structure of a dataset which can help in insight generation.

Any EDA comprises of the following steps
- Defining the problem statement
- Collecting data required for the problem
- Pre-processing of data
  - Pre-profiling
  - Processing data based on pre-profiling
  - Post profiling of data
  - Breaking down into high level topics based on problem statement
  - Performing univariate, bivariate and multivariate analysis on these topics to understand the data

An effective EDA performed on a dataset helps to identify relevant features that can be fed to our machine learning algorithms and generate a good model with high predictve power.


### Repository Overview

This repository is about EDA performed on Indian Premier League Data available between 2008 - 2018.
- It has a python notebook where all the coding has been done 
- It also has the relevant datasets used for this analysis

### Brief Overview of the steps followed in this project

There are 2 datasets used for the analysis. 'matches' dataset gives information on all the matches played in IPL between 2008 and 2018 i.e. information on the following:
- Season
- Venue
- City
- Teams
- Winner
- Toss Winner
- Winning margin
- Umpires

On the other hand 'deliveries' dataset gives ball by ball information on every match played during 2008 - 2018. In a nutshell it provides information on the following
- Runs scored per ball
- Extras by bowlers/fielding team
- Wickets taken
- Types of dismissals
- Venue
It basically provides individual records of players. 

The entire EDA process was broken down into 2 high level topics to find answers to the problem statement
- Univariate Analysis (analysing individual attributes)
- Bivariate Analysis (analysing 2 attributes together)

However, before analysing, Profiling and processing of data was undertaken.
After finding patterns and relationships in the data, EDA process was concluded with few conclusions as derived while analysing. Along with concluding insights, few actionable items were also suggested which could help in better performance of players or auctioning of players, etc.
