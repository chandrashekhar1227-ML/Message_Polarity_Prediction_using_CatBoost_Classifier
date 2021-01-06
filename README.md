# Message_Polarity_Prediction_using_CatBoost_Classifier
# Rank 1/190
The given data was all numerical. I first determined the correlation among all the independent variables that were very low, so I decided to include all the predictor variables. The given labels were imbalanced. To balance it, I used random over-sampling technique from the imblearn package. Then I divided the data set into 80:20 train and test ratio and built the model with different algorithms like Random Forest, XGB classifier, LightGBM and CatBoost. CatBoost was able to give high precision and recall. I did hyperparameter tuning using randomised search cv. One of the parameters gave me the highest accuracy and the final model was built using those parameters.
# Link to the Competition:
# https://www.machinehack.com/hackathons/message_polarity_prediction_weekend_hackathon_3/leaderboard
# Winners article link by Analytics india magazine:
# https://analyticsindiamag.com/message-polarity-prediction-winners/
