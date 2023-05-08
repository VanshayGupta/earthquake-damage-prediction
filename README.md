# Prediction of structural damage caused by the Gorkha earthquake

This project proposes a machine learning pipeline to predict the level of damage for buildings affected by the Gorkha Earthquake in Nepal in April 2015, based on geographic and structural information. An autoencoder model has been used to generate mappings between the geographic features, and preprocessing techniques like recursive feature elimination and normalization have been applied. Two ensemble classification models specialized for categorical data have been used i.e. CatBoost and LightGBM. The best test micro F-1 score of 0.7524 was found using LightGBM post hyperparamter tuning using Optuna, ranking in the top 2% of global submissions on DrivenData.
