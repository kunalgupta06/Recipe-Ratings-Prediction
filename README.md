# Recipe-Ratings-Prediction

This repository contains all the files and documentation necessary to understand, analyze, and build predictive models for the ratings of food recipes. The goal of this project is to predict the rating of a recipe based on various features such as recipe names, user reviews, and other relevant attributes.

Project Description
The project revolves around predicting the ratings of food recipes using a comprehensive dataset. I was tasked with exploring the dataset and developing models that can accurately forecast the ratings for each recipe. This project showcases the approach and methodologies used to achieve this goal.

Dataset Overview
The dataset is divided into two main files:

train.csv: The training set, including the target variable 'rating' and accompanying feature attributes.
test.csv: The test set, containing similar feature attributes but without the target variable 'rating', which is to be predicted.

Columns Description
RecipeNumber: Placement of the recipe on the top 100 recipes list
RecipeCode: Unique ID of the recipe used by the site
RecipeName: Name of the recipe the comment was posted on
CommentID: Unique ID of the comment
UserID: Unique ID of the user who left the comment
UserName: Name of the user
UserReputation: Internal score of the site, roughly quantifying the past behavior of the user
CreationTimestamp: Time at which the comment was posted as a Unix timestamp
ReplyCount: Number of replies to the comment
ThumbsUpCount: Number of up-votes the comment has received
ThumbsDownCount: Number of down-votes the comment has received
Rating: The score on a 1 to 5 scale that the user gave to the recipe. A score of 0 means that no score was given (Target Variable)
BestScore: Score of the comment, likely used by the site to help determine the order comments appear in
Recipe_Review: Text content of the comment
