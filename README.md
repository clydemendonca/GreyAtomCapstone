# Capstone Project
### Predictive Event Modelling - Propensity to watch a video in the next 2 days
### Recommendation Engine - Recommending 3 new videos to a user, based on the videos he/she has watched

## Problem Statement  
- Segment the audience of a content app based on its user’s propensity to watch a video in the next 2 days.
- Our goal is to not only identify users who are likely to convert but also target and convert users who are unlikely to convert. Hence, the features used to create the model should be actionable by a marketer.

## A Brief about the Data 
The directory contains event details for a Video Content app. As the user engages with the app, some of
his actions are recorded in detail.
For example, as soon as the user launches the app, an "AppLaunched" event is recorded which contains
details such as timestamp, os, device, country, userId etc.
When the user registers itself for the app, a "Registered" event is raised. Similarly when he views the
details of a video or an episode, a "VideoDetails" event is recorded. Also, when he starts watching a
video, a "VideoStarted" event is raised.
Many a time, app owners also engage with the customers via Push Notifications, SMS, emails etc. When
a user clicks on any such campaign, a UTM Visited campaign is recorded.

### Note : We are not able to provide more information on the data due to a Non Disclosure Agreement.

## Our Approach
RFM analysis is one such popular customer segmentation technique that can help retailers maximize the return on their marketing investments.
- Recency: Recency is the most important predictor of who is more likely to respond to an offer. Customers who have purchased recently from you are more likely to purchase again from you compared to those who did not purchase recently.
- Frequency: The second most important factor is how frequently these customers purchase from you. The higher the frequency, the higher is the chances of them responding to your offers.
- Monetary: The third factor is the amount of money these customers have spent on purchases. Customers who have spent higher are more likely to purchase based on the offer compared to those who have spent less.

User Based Collaborative Filtering
- User Based Collaborative Filtering uses that logic and recommends items by finding similar users to the target user (to whom we are trying to recommend videos). A specific application of this is the user-based Nearest Neighbor algorithm. This algorithm needs two tasks:
    1. Find the K-nearest neighbors (KNN) to the user.
    2. Recommend the videos that the neighbours of the target user have watched but the target user has not watched.


## Evaluation Metrics
- F1-score
- Segments: Minimum of 2 segments and a maximum 4 segments can be created
- Features: The goal of a marketer is to not only identify users who are likely to convert but also
    target and convert users who are unlikely to convert. Hence, the features used to create the
    model should be actionable by a marketer.
