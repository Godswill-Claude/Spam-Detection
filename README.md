# Spam-Detection

This project uses Naive Bayes model building to classify email messages as Spam or Not Spam.

Naive Bayes is a machine learning algorithm, specifically a classification algorithm, used in supervised learning. It is based on Bayes' Theorem and assumes that the features (predictor variables) in a dataset are conditionally independent of each other, given the class label (hence the term "naive"). Despite this "naive" assumption, it performs surprisingly well for many real-world applications.

## Dataset
A synthetic dataset of `messages` and the corresponding `labels` was used for the entire project.
A label of 1 means Spam, while 0 means Not Spam.

## Tools/Applications/Softwares/Packages Used for the Project
The python programming language, along with libraries such as Sci-kit learn, pandas, numpy, Seaborn and matplotlib, was used for the explorations and visualizations contained in this work.

## Key Insights for Analysis/Investigation
In this project, I endeavoured to find out the metrics used to classify an email message as Spam or Not Spam.

## Summary of Findings
The model evaluation score was zero, which is not surprising here because we are data-poor. Insufficient data was used for the training of the model. This highlights the need to train models with sufficient data for optimal performance.
