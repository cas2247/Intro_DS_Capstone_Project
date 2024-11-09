# Masters Intro to Data Science Capstone Project
This repository contains the code and results from our final capstone project for the Masters Intro to Data Science course at NYU Courant with Professor [Pascal Wallisch](https://github.com/Pascallisch).

## Project Overview
The overview and structure of this project (based on the course Sittyba) are as follows:  As part of a team of 2-5 members, we selected and analyzed a dataset of our choice to produce a project report of our findings while tying together the skills and techniques we've learned in this class. The project emphasizes finding a topic and rich dataset that bring “joy” and excitement to the analysis process.

Our project follows a suggested structure but allows flexibility in focus. The recommended structure includes:
	1.	Introduction
	2.	Hypothesis Testing Analysis
	3.	Regression Analysis
	4.	Machine Learning Analysis
	5.	Overall Summary and Conclusions

## Dataset
The dataset used in this project is the **Speed Dating Experiment** dataset, available on Kaggle. You can find it [here](https://www.kaggle.com/datasets/annavictoria/speed-dating-experiment).

### Dataset Description
This dataset, compiled by Columbia Business School professors Ray Fisman and Sheena Iyengar, explores the dynamics of “love at first sight” through speed dating experiments conducted from 2002-2004. Participants engaged in four-minute “dates” and then rated each other on six attributes:
	•	Attractiveness
	•	Sincerity
	•	Intelligence
	•	Fun
	•	Ambition
	•	Shared Interests

Participants were also asked whether they would like to see each date again. Additionally, the dataset includes questionnaire responses about demographics, dating habits, self-perception, beliefs on attractive qualities in a mate, and lifestyle.

For additional insights from the researchers, see their paper on [Racial Preferences in Dating](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=610589).

## Project Summary

Our project reveals intriguing patterns in how individuals evaluate romantic partners in a speed dating setting. Through a series of analyses, we explored gender differences in match likelihood and the role of shared interests in fostering connections:
	•	Gender Differences in Matching: Hypothesis testing showed that men were over 10% more likely than women to indicate a desire for a match, a difference that proved to be both practically and statistically significant.
	•	Importance of Shared Interests: Our analyses highlighted a strong correlation between a dater’s decision to match and the extent to which they shared preferences and common interests with their partner.
	•	Predicting Match Success: To assess whether a dater would want to match with their partner, we applied several classification models, including decision trees, support vector machines (SVM), k-means clustering, and neural networks. Among these, the SVM model was the most effective in predicting match outcomes based on preference and rating data collected after each date.

Our findings provide evidence for gender differences in dating behaviors and underscore the importance of shared interests in creating successful matches. Although these insights are engaging (and perhaps a bit humorous), a more comprehensive study on romantic attraction could involve alternative analytical methods or even a new experiment.

### Limitations

While the above findings are certainly engaging (and maybe even a little comical), if we were interested in a more thorough study of human romantic attraction, we might consider running our own experiment or using different analytical methods to derive more robust conclusions. 

The most significant assumption that we made in our analyses was that the result of each individual date was independently and identically distributed from every other. While mathematically convenient, this is less plausible in practice. For example, we might easily imagine that an individual’s dating experience is likely to change over the course of a speed dating event (a normally less than exciting date might appear so after a particularly dull one or vice versa). 

Perhaps the most significant limitation of this study, our dataset comprises the results of an experiment run on Columbia student volunteers - a convenience sample from a population that probably generalizes poorly to the broader American singles market or even to the NYU graduate population (since we are so much further downtown and therefore much cooler than our Morningside Height counterparts). To gain a clearer understanding of these issues, we would benefit from running our own experiment on a more random and representative sample to uncover the factors that truly influence love at first sight... or at the very least, the first 4 minutes.

For more analysis from Iyengar and Fisman, we invite you to read [Racial Preferences in Dating](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=610589).

