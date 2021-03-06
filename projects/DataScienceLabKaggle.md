[Home](../index.md)

# Data Science Lab Project

My Data Science Lab course had a inter-class Kaggle competition that I achieved the highest grade in. Initially I was skeptical I could perform well, as it was the first time I jumped into a true data science project and got my hands dirty. In addition, there was a huge school tradition and football game that weekend, which I reluctantly decided to skip in order to put more time into the project.

The first difficultly was exploring the data set; the features were not named, so there was no initial intuition for where to start. I began basic exploration techniques: building a correlation matrix, looking at the class imbalance, one-hot encoded potential categorical features.

The exploration gave me some insight but I needed a model for classifications. I tested various modeling techniques such as random forests, logistic regression, and gradient boosting. I spent a lot of time tuning the hyper-parameters to squeeze more out of the models. I even used some of my AWS student credit to run a grid-search of parameters on a faster cloud instance. In the end, my best scoring model was a stacking classifier that took the predictions of the tuned XGBoost, Gradient Boost classifiers and the default parameters of Logistic Regression and Random Forest. The model achieved a public ROCAUC score of 0.91761 and private score of 0.90283.

I was 6th on the leader board, but we were grading on both the placement and the report. Since I explored so many techniques and ideas, my report earned me the highest grade in the class. Skipping that football game turned out to be worth it!
