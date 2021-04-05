# NBA_Positions
Data and model files from Gaussian Mixture Model analysis of NBA player statistics. Related article available at https://medium.com/swlh/whats-your-basketball-personality-499fd943b34d?sk=68746a384a567065d61a6fd407ee976d

Included in this repository are:
1. mod10fit.Rds - the GMM model (fit with tidyLPA - https://data-edu.github.io/tidyLPA/) - useful for predicting class membership
2. ModelEstimatesByClass.csv - the estimated mean and standard error for each variable, by class, estimated by the model
3. cluster_data_2013-20.csv - the full dataset (scaled) of 2,234 season-level player observations used to calculate the model (the estimated position and probabilities for each position from the model have been added to the dataset)
