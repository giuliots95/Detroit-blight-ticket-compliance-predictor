# Detroit-blight-ticket-compliance-predictor
This repository contains the study on a binary classifier that predicts if a blight ticket issued by Detroit agencies is likely to be paid or not, based on historical data.
What I think is worth of attention, is the application of an evolutionary strategy to perform the hyperparameters research. Instead of using "sklearn" default techniques, like grid search or randomized grid search, I used an adapted version of the genetic algorithm provided in "sklearn-gen-opt" library, to optimize the parameters search.
