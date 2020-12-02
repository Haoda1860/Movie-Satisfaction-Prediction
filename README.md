# Movie-Satisfaction-Prediction

## Indroduction:
In this project, I am going to classify if the movies on the recommendation list are enjoyable based on the personalities of users. Once we integrate the personality features, the movie recommendation system would show more accurate recommendations. In our dataset, obviously the target variable is the “enjoy_watching” variable in the “personality” dataset. This Kaggle dataset, “2018-personality-data” provided by Arslan Ali, contains 1834 observations with 34 features and no missing values. The data description can be easily found on the homepage. However, 24 columns are the 12 movie IDs corresponding to the 12 rating scores. Therefore, in order to show the overall performance of the ratings, I took the average of them to get the new feature, “avg_ratings”. Finally, I have 9 features to predict the target variable and distinguish the target variable into two groups (enjoyable/not enjoyable) by the scores that greater or equal than/ less than 4, which makes sense because people rated 3 may not enjoy the list of movies too much. Beside the target variable, in the 9 features, 8 of them are categorical features representing the survey scores and 1 of them is the continuous variable representing the average ratings of the movies.


## Project structure:
"report" file contains the detailed report. I highly recommend to review this file at the first;
"data_proj" file contains 2 datasets in use;
"results" file contains the models that I used in the project;
"src file" contains the jupyter-notebook python file;
"figures" file contains all plots that I generated in the project;


## Software Versions:
Python version is 3.8.3

Package version: 
numpy version 1.18.5;
matplotlib version 3.2.2;
sklearn version 0.23.1;
pandas version 1.0.5;
shap version 0.35.0;
