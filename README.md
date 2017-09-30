# Springboard.com Data Science Program

This Github repository contains the coursework completed in the [Springboard data science online bootcamp](https://www.springboard.com/workshops/data-science-career-track/).  The program covers data science topics including machine learning, inferential statistics and data storytelling.  Two capstone projects were completed with the guidance of a data science mentor.

## Data wrangling

Working with messy raw data: extraction, cleaning, and dealing with missing, invalid or corrupted values.

### Working with data in files

Used Pandas and other Python packages for data wrangling operations.

* [JSON based data exercises](https://github.com/vincelaird/springboard/blob/master/data_wrangling_json/sliderule_dsi_json_exercise.ipynb) - convert JSON from file into dataframe and review.
* [XML based data exercises](https://github.com/vincelaird/springboard/blob/master/data_wrangling_xml/sliderule_dsi_xml_exercise.ipynb) - parse XML from file into dataframe and review.

### Working with data in databases

Utilized relational and nonrelational databases to attain and analyze data.

* [Mode Analytics: Drop in user engagement](https://modeanalytics.com/vincelaird/reports/fbf0fd3327dd/runs/23fa4c90a7d2) - solution to the SQL Analytics training: [Investigating a Drop in User Engagement](https://community.modeanalytics.com/sql/tutorial/a-drop-in-user-engagement/).

## Data storytelling

Telling stories with data, including exploration, communication and presentation.

### Telling the story of odds changes in MLB games, April 2016

* [Capstone project: MLB odds changes](https://github.com/vincelaird/springboard/blob/master/capstone/Data%20story.ipynb) - data story of changes in odds leading up to contest start time of MLB games in April 2016.

## Inferential statistics

Introduction to statistical inference, hypothesis testing, regression and correlation and their applications such as in A/B testing.

### Exploratory data analysis projects

Used inferential statistics and hypothesis testing to elicit insights from data and create data stories.

* [Human body temperature](https://github.com/vincelaird/springboard/blob/master/human_temp/sliderule_dsi_inferential_statistics_exercise_1.ipynb) - analysis of human body temperatures and the concepts of hypothesis testing, confidence intervals, and statistical significance.
* [Racial discrimination](https://github.com/vincelaird/springboard/blob/master/racial_disc/sliderule_dsi_inferential_statistics_exercise_2.ipynb) - analysis to establish whether race has a significant impact on the rate of callbacks for resumes.
* [Reduction in hospital readmissions](https://github.com/vincelaird/springboard/blob/master/hospital_readmit/sliderule_dsi_inferential_statistics_exercise_3.ipynb) - critique of analysis of data and recommendations for reducing hospital readmissions rate.

## Machine learning

Core machine learning techniques; covered various supervised and unsupervised learning algorithms, and best practices for applying machine learning.

### Linear and logistic regression

Covered supervised machine learning algorithms including linear and logistic regression, support vector machines, decision trees and random forests.

* [Linear regression using Boston housing data set](https://github.com/vincelaird/springboard/blob/master/linear_regression/Mini_Project_Linear_Regression_complete.ipynb) - linear regression models, predictions, re-sampling methods, train-test and cross validation using housing values in suburbs of Boston.
* [Heights and weights using logistic regression](https://github.com/vincelaird/springboard/blob/master/logistic_regression/Mini_Project_Logistic_Regression_complete.ipynb) - logistic regression and classifiers using a dataset of heights and weights of males and females.

### Bayesian methods and text data

* [Predicting movie ratings from reviews using Naive Bayes](https://github.com/vincelaird/springboard/blob/master/naive_bayes/Mini_Project_Naive_Bayes_complete.ipynb) - text analysis using a subset of movie reviews from the Rotten Tomatoes database.

### Unsupervised learning

* [Customer segmentation using clustering](https://github.com/vincelaird/springboard/blob/master/clustering/Mini_Project_Clustering_complete.ipynb) - customer segmentation using a dataset containing information on marketing newsletters/e-mail campaigns (e-mail offers sent to customers) and transaction level data from customers.

## Capstone project 1: Sports betting line movement

Sports betting odds change throughout the day; this capstone project set out to find if this line movement could be predicted with any amount of accuracy using machine learning techniques.

### Project overview

* [Project proposal](https://github.com/vincelaird/springboard/blob/master/capstone/Sports-betting-line-movement-project-proposal.pdf) - problem this project aims to solve is: when is the optimal time to place a moneyline bet on a baseball game based on past odds; are odds trending up, down, or are they stationary?  Will this trend continue, and why is this important?

### Data wrangling

* [Data from past and present, an overview](https://github.com/vincelaird/springboard/blob/master/capstone/Data-wrangling.pdf) - brief summary of where historical odds are found, and where current odds can be collected.
* [Data collection web app](https://github.com/vincelaird/ds-mlb) - Node.js app to collect MLB odds every minute.

### Data storytelling

* [MLB odds changes](https://github.com/vincelaird/springboard/blob/master/capstone/Data%20story.ipynb) - data story of changes in odds leading up to contest start time of MLB games in April 2016.

### Inferential statistics

* [Review of April 2016 data](https://github.com/vincelaird/springboard/blob/master/capstone/Inferential%20Statistics.pdf) - testing the adage of betting favorites early and dogs late: this strategy wouldn't have worked during the first month of the 2016 MLB season.
* [Jupyter Notebook for inferential statistics](https://github.com/vincelaird/springboard/blob/master/capstone/Inferential%20Statistics.ipynb) - details of analysis done on historical MLB data.
* [Milestone report](https://github.com/vincelaird/springboard/blob/master/capstone/Milestone-1.pdf) - review of project at the midway point: steps taken, project progress and goals for completion.

### Project completion

* [Sports betting line movement final project summary](https://github.com/vincelaird/springboard/blob/master/capstone/Capstone%201%20Final%20Submission.pdf) - completed document detailing the process and results from this project. The Bayesian structural time series (BSTS) model was the primary machine learning technique used. Summary: check the trend before betting!
* [Sports betting line movement blog post](https://www.linkedin.com/pulse/i-know-whos-winning-todays-baseball-game-want-maximize-vince-laird/) - project details in layman's terms.
* [Odds for one team: Arizona Diamondbacks](https://github.com/vincelaird/springboard/blob/master/capstone/ari-various-charts.ipynb) - details of odds movements for the first 53 games for one specific team, the Arizona Diamondbacks.

## Advanced topics in machine learning

Recommendation systems, anomaly detection, time series analysis and basic neural networks.

### Recommendation systems

Recommendation systems are use by Amazon, Netflix, Facebook and Twitter to recommend content a user might like; this portion of the course shows an introduction to how they work.

* [Minimal recommendation engine](https://github.com/vincelaird/springboard/blob/master/pycon2015_tutorial322/pycon.ipynb) - overview of Numpy and Pandas and how to use both to build a minimal recommedation engine, using the MovieLens 1M dataset, which contains 1 million ratings collected from 6000 users on 4000 movies.
* [Reco systems evaluation methods](https://github.com/vincelaird/springboard/blob/master/pycon2015_tutorial322/questions.ipynb) - implementation of collaborative functions to evaluate results of the minimal recommendation engine.

### Time series

* [Time series analysis tutorial](https://github.com/vincelaird/springboard/tree/master/time_series) - notebooks used for the [SciPy 2016 tutorial by Aileen Nielsen](https://www.youtube.com/watch?v=JNfxr4BQrLk), starting with an introduction to time series functions in Pandas and covering the basic principles, including forecasting using autoregressive algorithms.

## Data science at scale

Introduction to the fundamentals of Spark and building distributed applications at scale.

### MapReduce with Spark

* [Exercises in PySpark and MapReduce](https://github.com/vincelaird/springboard/blob/master/spark/pyspark_complete.ipynb) - installation of Spark, working with RDDs, determining characteristics of the play Julius Caesar using MapReduce and an introduction to utilizing machine learning algorithms with Spark.

## Capstone project 2: building a recommendation system from session data

How would an e-commerce website recommend products to a user if all that was available was session data from other users? This project utilizes the [RecSys 2015 Challenge](https://recsys.acm.org/recsys15/challenge/) dataset to build a recommendation system based on similarity distance measurements of items.

### Project overview

* [Exploratory data analysis](https://github.com/vincelaird/springboard/blob/master/capstone2/Capstone%202%20milestone%20notebook%20EDA.ipynb) - Notebook details the challenges of this dataset: 33M rows in 'clicks' dataset, only 5.5% of sessions resulting in buy events.

### Project completion

Subsetting the original dataset and using content-based recommendation resulted in similarity scores for items.

* [Recommendation system final project summary](https://github.com/vincelaird/springboard/blob/master/capstone2/Capstone%20Project%202%20-%20Final%20submission.pdf) - steps taken to setup Amazon Web Services to deal with the large dataset, details of subsetting and utilizing cosine and Jaccard similarity scores to rank items that are most similar to other items, based on clicks and buys.
* [Recommendation system Notebook](https://github.com/vincelaird/springboard/blob/master/capstone2/Capstone%202%20recommendation%20system.ipynb) - Notebook created to show details of item similarity scores. 
* [Recommendation system slide deck](https://github.com/vincelaird/springboard/blob/master/capstone2/Capstone%20project%202%20-%20recommendation%20system%20slides.pptx) - Powerpoint slides showing details of recommendation system project.

## Take-home challenges

 Take-home assignments are generally part of the data science interview process; below are three that were done within the Springboard program.

* [Ultimate Inc. data science challenge](https://github.com/vincelaird/springboard/tree/master/ultimate_challenge) - exploratory data analysis, experiment and metrics design, and predictive modeling exercises for a fictional Uber-like ride sharing company.
* [KeepUp data science challenge](https://github.com/vincelaird/springboard/blob/master/keepup_challenge/KeepUp.ipynb) - analysis of [Amazon dataset](http://snap.stanford.edu/data/amazon-meta.html) to improve categorization, examine trustworthiness of ratings and optimize methods of product presentation.
* [Relax Inc. data science challenge](https://github.com/vincelaird/springboard/blob/master/relax_challenge/Relax.ipynb) - determine factors that predict user adoption based on user and user engagement data; utilized classification algorithms such as XGBoost and decision trees, and evaluated output using accuracy scores.
