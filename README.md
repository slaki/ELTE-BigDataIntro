# ELTE-BigDataIntro

This repository only contains the data file and the ipython/jupyter notebook used in the live coding example.


Our goal was to create a model that predicts if a plane lates or arrives in time.
To this end, we first introduced a new column (aka variables) called "is_late" where is "is_late" = 0.0 if the plane arrives in time and 1.0 if it is delayed.

In supervised learning, to build and validate a model, we generally need to train the model on a train set and then validate it on independent test data. In this example, RandomForest method was choosen to build a predictor for "is_late" variable. In the first try the input features carry the non-string variables only.
