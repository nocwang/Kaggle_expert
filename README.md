# Kaggle codes
https://www.kaggle.com/competitions


# Histopathologic Cancer Detection
Identify metastatic tissue in histopathologic scans of lymph node sections
https://www.kaggle.com/c/histopathologic-cancer-detection

## create an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans. 
The data for this competition is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset (the original PCam dataset contains duplicate images due to its probabilistic sampling, however, the version presented on Kaggle does not contain duplicates).
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.
The competition will conclude March 30, 2019 at 11:59 PM UTC.

In this dataset, you are provided with a large number of small pathology images to classify. Files are named with an image id. The train_labels.csv file provides the ground truth for the images in the train folder. You are predicting the labels for the images in the test folder. A positive label indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image.
The original PCam dataset contains duplicate images due to its probabilistic sampling, however, the version presented on Kaggle does not contain duplicates. We have otherwise maintained the same data and splits as the PCam benchmark.

# Women in Data Science (WiDS) Datathon 2019
- Top 20 among 203 teams
- Our Private Leaderboard AUC is 0.99923 and Best Kaggle Private Leaderboard AUC is 0.99957.
- Developed deep learning models (convolutional neural network including Resnet18, Resnet50, Resnet101) and used ‎Transfer Learning techniques to analyze and predict the presence of oil palm plantations in satellite imagery using the fastai library.

The challenge is to create a model that predicts the presence of oil palm plantations in satellite imagery. Planet and Figure Eight have generously provided an annotated dataset of satellite images recently taken by Planet satellites. The dataset images are 3-meter spatial resolution, and each is labeled with whether an oil palm plantation appears in the image (0 for no plantation, 1 for any presence of a plantation).

The datathon task is to train a model that takes as input a satellite image and outputs a prediction of how likely it is that the image contains an oil palm plantation. Labeled training and test datasets are provided for model development; you will then upload your predictions for an unlabeled test set to Kaggle and these predictions will be used to determine the public leaderboard rankings, and the final winners of the competition.

# Home Credit Default Risk
- Bronze medal. 
- Developed the ensemble model to predict the probability that each applicant will repay a loan.
- My Private Leaderboard AUC is 0.79659 and Best Kaggle Private Leaderboard AUC is 0.80570.
https://www.kaggle.com/c/home-credit-default-risk

## makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target. August 29, 2018 - Final submission deadline.

application_test.csv
48.7k x 121
application_train.csv
308k x 122
bureau.csv
1.72m x 17
bureau_balance.csv
27.3m x 3
credit_card_balance.csv
3.84m x 23
HomeCredit_columns_description.csv
219 x 5
installments_payments.csv
13.6m x 8
POS_CASH_balance.csv
10.0m x 8
previous_application.csv
1.67m x 37
sample_submission.csv
48.7k x 2


# Porto Seguro’s Safe Driver Prediction
- Bronze medal. 
- Developed the ensemble model (based on XGBoost, Neural Networks) to predict the probability that a driver will initiate an auto insurance claim in the next year.
https://www.kaggle.com/c/porto-seguro-safe-driver-prediction

## build a model that predicts the probability that a driver will initiate an auto insurance claim in the next year. 
Porto Seguro, one of Brazil’s largest auto and homeowner insurance companies, completely agrees. Inaccuracies in car insurance company’s claim predictions raise the cost of insurance for good drivers and reduce the price for bad ones.
Submissions are evaluated using the Normalized Gini Coefficient. November 29, 2017 - Final submission deadline.

In the train and test data, features that belong to similar groupings are tagged as such in the feature names (e.g., ind, reg, car, calc). In addition, feature names include the postfix bin to indicate binary features and cat to indicate categorical features. Features without these designations are either continuous or ordinal. Values of -1 indicate that the feature was missing from the observation. The target columns signifies whether or not a claim was filed for that policy holder.

# Personalized Medicine: Redefining Cancer Treatment
Natural Language Processing and Classification: Using an expert-annotated knowledge base provided by Memorial Sloan Kettering Cancer Center (MSKCC), built multiclass classification model with XGBoost and Keras to classify genetic mutation based on evidence from text-based clinical literature. Current public leaderboard score (Logarithmic Loss) is 0.56402, ranking top 5%.

Feature Extraction: counting/TF-IDF/SVD reduced TF-IDF NLP-related features
Feature Selection: feature importance determined by VarianceThreshold/RandomForestClassifier


