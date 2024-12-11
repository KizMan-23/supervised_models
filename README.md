supervised model is a machine learning approach which is trained by using pre-labelled data to predict on unseen data.

TYPES OF SUPERVISED TECHNIQUES
1. Classification
2. Regression

Supervised_Models contains projects that have utilized either of the two types of supervised techniques to predict on unseen data. In [nba_data](nba_data.ipynb) and [nba_cleaning](nba_cleaning_1.ipynb), NBA dataset is loaded into jupyter notebook, using python frameworks like pandas, the data was prepared and cleaned to be usable for futhur model training and prediction

![nba_cleaning ss2](https://github.com/user-attachments/assets/6565c222-02ca-47a5-9578-2b48d980e0c2)
![ss3](https://github.com/user-attachments/assets/0a5d4068-9796-44e0-8c9a-039397e135d1)

cleaning dataset is a very important stage for data uniformity, offering consistency in data used for training and testing models. 

[mvp_prediction](mvp_prediction.ipynb) this is the training of a regression model to predict the next Most Valuable Player(MVP) lineup for the NBA. The model is trained by using past data and metrics on previous MVPs in correlation to their team performances. 
The model training employed the powers of Linear SVR and KNeighbors Regression from scikit-learn framework to determine the better perfomed model in predicting the MVP for the NBA using past data. The models were fine-tuned using a robust GridSearchCV to fined the model parameters thus improving accuracy of the model

![optimization](https://github.com/user-attachments/assets/2c2ebe39-c4ed-4ab8-9795-78f5074343a4)

![feature impt](https://github.com/user-attachments/assets/f7e1ce0a-b01f-4812-801b-c0066606aad6)

backtesting the models

![backtesting](https://github.com/user-attachments/assets/b48537bb-50c8-49b9-8302-a21d49ce1307)


supervised_models repo contains other classical machine learning prediction works such as [Premier_league Prediction](premier_league_predictions.ipynb). The premier_league prediction is a robust model for predicting which team will win the next match. The model can serve to provide better predictive information for game betting markets, provided the accuracy improves.
The Premier League is the English Football league that comprises of 20 teams that are to play 38 matches within the leagues calender to determine the champion for the premier league.
The model is trained on a dataset I scraped from the football website for years of the league standing tables and teams' performances

![premier league 1](https://github.com/user-attachments/assets/8a20ba2b-113a-4efc-a728-a65b2da20ef8)

In training the model, different regression techniques from scikit-learn were tested to determine the best technique that offers the optimal accuracy for the dataset..

![pr lg models](https://github.com/user-attachments/assets/21aecc08-d1bd-437d-a85e-68c0e4eb2bc5)

setting the target for the model prediction

![pr_lg target](https://github.com/user-attachments/assets/ec11e719-a3f2-4261-8074-c6704990583b)

![pr lg preds](https://github.com/user-attachments/assets/0ce4fbd6-305c-47ef-9aa0-a90e45b353b6)

[Spotify Trend](spotify_trend.ipynb) Is an analysis of artists' tracks and albums released across years and its performances across different streaming platforms. This analysis and modeling helps to understand the reach of a tracks and possible returns on investment in making such tracks for artist. The analysis gives insight to platforms that can be of more importance to artists in reaching higher listeners and consumers.

![sportify](https://github.com/user-attachments/assets/47d6376c-06db-4928-ad52-280f6c53a0f2)

[Student Performance](student_performance.ipynb) Is a comprehensive and indepth analysis of a dataset of students' academic performance, grouping the students according to thier Grade Classes. For every student, there are factors that could affect their class room performances in a positively or negatively manner. In this analysis, I looked into the different factors that influence the output of the students in thier grades such as parental support, voluntering works, participating in extracurricular activites etc. 

![students corr](https://github.com/user-attachments/assets/83ba33b0-eb98-4524-be9c-215d69912d58)

I also, developed a regression model to predict the grade level of the students based on several factors that affect students as factors. More Importantly, I applied Monotonic Constraint of the HistGradientBoostingRegressor to the model to influence the weight of each feature in relation to the target.

![mono_cst](https://github.com/user-attachments/assets/c06f010a-d059-4dcb-b948-6ef2554d9f76)

