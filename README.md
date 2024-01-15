# Paper_review-ML
Machine learning algorithms to predict the evaluation of paper review dataset 
# Breathly description 
In the notebook I made a preliminary EDA phase, in this phase, I chose the best feature to perform predictions. 
After that, the main phases that I am focused on are Model Selection, Model Assessment and Test Evaluation.
# Text Feature
The Text Feature is the most important of the dataset shown, I made a previous moment a vectorization by TF-IDF and a dimensionality reduction using a PCA variant 
on the train set and tested the performance (the model assessment phase) on the development set. 
# Test Evaluation 
After the choice of the best estimator based on the value of the mean cross-validation score and the development score after labels prediction, I used the model trained on the whole train dataset (train + dev) and tested it on the test set 
