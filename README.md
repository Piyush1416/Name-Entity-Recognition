# Name-Entity-Recognition

Name Entity Recognition (NER) is the process of finding person names, organization names, location, time from unstructured data.

In current market we have numerous packages to detect NER like Stanford CORE-NLP, Spacy, Polyglot, NLTK-NER, but none of them are that great considering accurately identifying names or at worst not identifying them at all.

I agree that no package is complete and could solve entire problem,as large amount of data from different domain is been continuously generated, but we need to find a way where user gets more control over data. So that we can retrain a model on domain specific data and cover the gap of prediction inaccuracy.

To solve this problem, I thought of taking a novel step towards using ML model for solving NER issue.

I have used NER dataset found on kaggle and attached it in my repository above.

 I have used both Out-of-core Algorithms and Regular in-memory processing Algos in notebook.
 Out-of-core Algorithms are designed to process data that is too large to fit into a single computer memory that support partial_fit method.
 
Out-of-core Algorithms Used =====>

1] Naive Bayes classifier for multinomial model

2] Perceptron

3] Linear classifiers with SGD training


Regular ML Algos with fit method=====>

1] Logistic Regression

2] Random Forest
