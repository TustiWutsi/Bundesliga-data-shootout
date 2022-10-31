# Bundesliga-data-shootout

This repo is based on the Kaggle challenge 'DFL - Bundesliga Data Shootout' : https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout

The objective is to train a video classifier able to detect football match events (play / challenge / throw-in), thanks to full Bundesliga match videos provided by the league. 

This kind of event annotation project could be a real breakthrough for the Football industry for 2 main reasons:
- it could enable data from currently unexplored competitions (youth or semi-professional leagues for instance)
- it could save time, effort and cost since event data is mostly collected manually

This code does not aim at creating the most performing Deep Learning model, but shows the different mandatory steps, from video and frames preparation to final model prediction.

Part of the methodology and the code comes from this publication from Pulkit Sharma : https://www.analyticsvidhya.com/blog/2019/09/step-by-step-deep-learning-tutorial-video-classification-python/#h2_1
