# IBM-322 Project

## Stats Analysis (Predicting run and wicket on next ball based on statistics)
stats_analysis.ipynb - Logistic Regression, SVM and MLP classifier on ball by ball features.

stats_analysis_with_pca.ipynb - Logistic Regression, SVM and MLP classifier on ball by ball features on dataset post PCA.

## FormAnalysis
FormAnalysis.ipynb: We create a class to perform (general n-gram) Bigram and Trigram analysis on the dataset. 

## Classification (ball granularity)
prediction.ipynb: This file contains code to merge the outputs of stat analysis and form analysis together and computes the various different probabilities using several models. 

## Overs analysis (Predicting run in an over)
Over_Grouping.ipynb - Converting Dataset in the format desired for overwise prediction.

overs_stats_analysis.ipynb - Applying classification algorithms (Logistic Regression, SVM and MLP classifier) on overwise features.

overs_stats_analysis_with_pca.ipynb - Applying classification algorithms on overwise features on the dataset post PCA.

overs_linear_regression.ipynb - Applying linear regression on overwise features.

overs_linear_regression_with_pca.ipynb - Applying linear regression on overwise features with dataset post PCA.

overs_MLPregressor.ipynb - Applying MLP regression on overwise features.

overs_MLPregressor_with_PCA.ipynb - Applying MLP regression on overwise features on dataset post PCA.

## Total run stats (Predicting total runs in an inning)
total_runs_stats.ipynb - Applying MLP regression on overwise features and then getting total runs in an innings on dataset obtained by Over_Grouping.ipynb.

