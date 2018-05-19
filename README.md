# Statistical-Analysis-EPL-data
  We will be using Excel, SAS (University Edition) and Tableau for this analysis. 

## INTRODUCTION

#### Objective

The main purpose of the project is to perform Analysis on a specific set of data mainly using the Statistical methods and provide inferences from the results obtained. 

#### Executive Summary

This report summarizes the statistical modeling and analysis results associated with English Premier League. The purpose of this report is to document implemented sampling design and all corresponding data modeling and inference techniques used during our statistical analysis.
English Premium League EPL is a professional league for men’s association football clubs. The primary role of the English Premier League is to organize the football competition between the 20 Clubs that make up the league. In revenue terms, it is now the third largest league in the world, behind the US Major League Baseball and National Football League (American Football). 

The data for our analysis has been derived from two sources  – ‘The official EPL website’ and ‘EPL Stats blog’.

#### Data Description

The main reason for choosing this data set is, the Premier League is the most-watched sports league in the world and we felt it would be interesting to do a statistical analysis on this data. 

The Dataset used for the performing the analysis is a comprehensive data set which contains the details of each match EPL (Match level) has hosted for the years between 2013-2017. The data for each year (2013-2014, 2014-2015, 2015-2016, 2016-2017) is downloaded from the data source mentioned below and downloaded files are merged to form a single file for better analysis. Also, we are using EPL dataset at Season level for the same years which is giving us the Table standings of Teams and summary for each team for that year with their spending. 

Initial source of Data source - http://www.football-data.co.uk/englandm.php and http://www.footstats.co.uk/index.cfm?task=league_full

The initial datasets are available : https://github.com/aparnaadiraju92/Statistical-Analysis-EPL-data/tree/master/Initial%20Datasets

#### Data Exploration
Apart from cleaning and normalizing the data we have performed feature engineering at several levels of data to make sure our analysis provides a valuable insight. (example feature: ‘Booking Points’ which is actually derived from valuating the  yellow, red cards and other fouls which in turn play a vital role in match result. This feature helps SAS to identify the significance and severity of an offence).

## Analysis tasks:

Our Analysis include several interesting tasks like: 

*1.	Identify the factors which will predict the Final match result.  
*2.	Clustering the referees into Harsh referee and Lenient referee based on the Fouls committed by the teams and Booking Points given by the referee in the matches over the seasons. 
*3.	Does the type of Referee (clustered in the above task) play a role in predicting the Final match result? 
*4.	Analyze if Full Time match result and type of match are dependent. Identifying the established sport rivalries and analyzing results from the derby matches and the matches played by the derby teams against other teams as Home and as Away.  
*5.	Analyzing if Betting result and Full-Time match result are dependent. Observe if there is any moderation effect on the relationship between Full-Time Goal Difference and Half-Time Goal Difference. 
*6.	Identifying how the Spending (i.e., Player wages) by each team impact Table standings each season. Does a team that spends more money on its players end up qualifying for Champions League i.e., being in the top 4 teams list on the league table?

These analyses will help everyone to have a deeper insight on match level and league level statistics. 
