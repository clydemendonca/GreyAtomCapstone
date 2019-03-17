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

## Our Approach


## Evaluation Metric
- F1-score
- Segments: Minimum of 2 segments and a maximum 4 segments can be created
- Features: The goal of a marketer is to not only identify users who are likely to convert but also
    target and convert users who are unlikely to convert. Hence, the features used to create the
    model should be actionable by a marketer.
