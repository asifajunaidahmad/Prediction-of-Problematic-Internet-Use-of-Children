# Prediction-of-Problematic-Internet-Use-of-Children
Predict the level of problematic internet usage exhibited by children and adolescents, based on their physical activity
Developed a predictive model capable of analyzing children's physical activity data to detect early indicators of problematic internet and technology use. This will enable prompt interventions aimed at promoting healthier digital habits.

# Dataset
Data is taken from kaggle Child Mind Institute.

# Model
CatBoostRegressor, XGBRegressor, VotingRegressor

# Evaluation
quadratic weighted kappa computed with three matricesO,W,E and N with the number of distinct labels.
