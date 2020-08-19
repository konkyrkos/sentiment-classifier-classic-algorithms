# Sentiment Classifier using Classic Algorithms

This repository provides my solution for the 2nd Assignment for the course of Text Analytics for the MSc in Data Science at Athens University of Economics and Business.

Development of a sentiment classifier for tweets using the "Sentiment 140" dataset provided by Stanford University.

Created features corresponding to words and used feature selection and centroids of pre-trained word embeddings.  

Tuned most hyperparameters used in the classifiers below either with grid search or using experiments.

## Classifiers 

1. DummyClassifier
2. SGDClassifier (Logistic regression)
3. RandomForestClassifier
4. MultinomialNB

## Classifier metrics

Precision, recall, F1 scores for each class and classifier, using a classification threshold t = 0.5 for each class in probabilistic classifiers, computed on the training, development, and test subsets.

## Classifier macro-average metrics

Macro-averaged precision, recall, F1 scores for each classifier, again using a classification threshold t = 0.5 for each class in probabilistic classifiers, computed on the training, development, and test subsets

## Statistical significance tests

Bootstrap statistical significance tests to check if the difference between the test macro-averaged F1 of the best (in terms of test macro-averaged F1) classifier (e.g., logistic regression) and the test macro-averaged F1 of each other classifier (or baseline) you experimented with is statistically significant (p-value < 0.01)

## Learning curves

Learning curves for macro-averaged F1 computed on (i) the training
data the classifier has encountered, and (ii) the entire development subset.

## Precision recall curves

Precision-recall curves using macro-averaged precision and recall, computed on the test subset. AUC values.

## Preprocessing & Statistics
Statistics about the datasets (e.g., average document length, number of training/dev/test documents, vocabulary size) and preprocessing of data

