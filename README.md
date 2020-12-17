# Titanic - Machine Learning from Disaster
Current state: *in progress, new model in development*
## About:
The model is to predict survival for each person in dataset of titanic passengers, which includes the following details: ticket class, sex, age in years, number of siblings/spouses/parents/children on Titanic, ticket number, passenger fare, cabin number, port of embarkation.
## Model:
Current model is represented as a classical 3 layer perceptron, which holds an accuracy of 73%.

Hyperparameter | Value
---|---
Learning rate | *1e-2*
Optimizer | *Adam, beta1=0.9, beta2=0.999, eps=1e-6*
Number of epochs | *100*
Batch | *the whole dataset split*
## Todo:
Current goal is to examine other possible algorithms that are applicable to a problem, evaluate them by their possible effectivness in terms of the challenge, and implement the one of them to improve acuracy.
## References:
[Competition page](https://www.kaggle.com/c/titanic/overview)
