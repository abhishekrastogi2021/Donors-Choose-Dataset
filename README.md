# Donors-Choose-Dataset

DonorsChoose is a non-profit organisation in United States where teachers submit huge amount of project proposals in diffrent subjects for funding. These projects verified by Volunteers/domain and confirm if this can be posted on DonorsChoose websites or not. 

As project proposals are huge every year, a machine learning model required to rectify if a submitted project can be approved or disapproved based on old datapoints which has lots of relative features. In case of disapproval, projects send back to teachers to provide more justifications and approved projects posted to websites at www.donorschoose.org. Even if ML model cannot justify project status it goes to domain experts for verification. 

Below operations performed on Dataset:

1. Basic dataset analysis.
2. Univariate analysis on each feature.
3. Data Preprocessing.
4. Data Featurization.
5. t-SNE Plotting.
6. Data Splitting.
7. Applied different Machine Learning models on dataset and performed hyperparameter tuning.

Below Models applied on Dataset:

1. Brute force K Nearest Neighbour(KNN) and applied feature selection with SelectKBest.
2. Naive Bayes and applied feature_log_proba to get the top 10 positive and negative features with their names. 
