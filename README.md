# EquipmentPricePrediction_Regression
Sample Regression workflow for heavy equipment price prediction


This notebook performs regression analysis to predict heavy-equipment machine prices. The data is taken from the Blue Book for Bulldozers Kaggle Competition: "The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration. The data is sourced from auction result postings and includes information on usage and equipment configurations."

This notebook is adapted from Jeremy Howard's fastai ML course. Some of the fastai dependencies are removed for performance comparisons and some of the fastai library functions are included here to make the notebook more self-contained. Such functions are attributed.



Because this dataset was used in a (now closed) kaggle competion, the scores above can be compared with the leaderboard for this competition: https://www.kaggle.com/c/bluebook-for-bulldozers/leaderboard

An RMSLE of 0.217 (shown in notebook)  would have been sufficient to win this competition at the time it was run. Of course, the test set used here is not the same as that used in the original competion, plus I have selected the test data as a random subset of the overall training data provided. In the original competition the test set did not chronologically overlap with the training set. The result is that a better RMSLE score is to be expected. Nonethless the standard out-of-the-box performance is impressive.This is testament to the power of sklearn library and the default RandomForestRegresor implementation.
