# Deploy Machine Learning Models with Django

This code is inspired from the tutorial available at [deploymachinelearning.com](https://deploymachinelearning.com)

This web service makes Machine Learning models available with REST API.

- it keeps information about many ML models in the web service. There can be several ML models available at the same endpoint with different versions. What is more, there can be many endpoint addresses defined.
- it stores information about requests sent to the ML models, this can be used later for model testing and audit.
- it has tests for ML code and server code.
- it can run A/B tests between different versions of ML models.

## The code structure

In the `research` directory there are:

- code for training machine learning models on Adult-Income dataset [link](https://github.com/JAY301/ml_service/blob/main/research/train_income_classifier.ipynb)
- code for simulating A/B tests [link](https://github.com/JAY301/ml_service/blob/main/research/ab_test.ipynb)

In the `backend` directory there is Django application.
