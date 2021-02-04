# Climate Change Belief Analysis

## Abstract

Companies are looking to create products and services that are environmentally friendly. They would thus like to understand their consumers' view on climate change. To address this, we are going to create Machine Learning models that are able to classify whether or not a person believes in climate change, based on their novel tweet data. Correct classification of a tweet will help companies understand consumer sentiment, which will further guide their business strategies.

We started off by exploring the text data, preprocess the text data using NLP tools and then trained base models. Lastly, we tried tuning hyperparameters to try and improve the performance of the models. Our top five models are the LinearSVC, SVC, Random forest, logistic regression and a sequential neural network that we have trained. The performance metric that we were more interested in was the weighted average f1 score. The Built models are to be deployed to a Streamlit application which can be used remotely through the use of an AWS ec2 instance.
