# 309Final

This project predicts whether birds are feeding based on environmental and ship-related conditions using several machine learning classification models. The main objective is to compare different models and determine which one best captures patterns in bird feeding behavior.

The data comes from the 2026 TidyTuesday collection and includes bird observations, ship movement data, and environmental conditions such as wind speed, sea state, precipitation, and air temperature. 

Five classification models were trained using 5-fold cross-validation: logistic regression using all predictors, logistic regression with a reduced set of predictors, decision tree, random forest, and k-nearest neighbors (k-NN). All models were evaluated using ROC (AUC) as the primary metric during training.

The random forest model performed best overall, achieving the highest AUC and accuracy on the test set. This indicates that it was the most effective model for distinguishing between feeding and non-feeding behavior.

These results help identify environmental conditions associated with bird feeding behavior. This type of analysis can support ecological monitoring, improve understanding of animal behavior, and inform future conservation and data collection efforts.
