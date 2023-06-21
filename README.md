# Junky_Union_14thProject
Film Junky Union, a new community for classic film fans, is developing a system to filter and categorize film reviews. Their main mission is to train a model that can automatically detect negative reviews. You will be using the IMBD movie review dataset with polarity labeling to create a model that can classify reviews as positive or negative. This model should have an F1 score of at least 0.85.

Based on the results of the model creation experiment using four models, here is a summary of the F1 scores:
  1. Model 1 - NLTK, TF-IDF, and LR produced an F1 score of 0.94 (train) and 0.88 (test)
  2. Model 2 - spaCy, TF-IDF, and LR produced an F1 score of 0.93 (train) and 0.88 (test)
  3. Model 3 - spaCy, TF-IDF, and LGBM produced an F1 score of 0.91 (train) and 0.88 (test)
  4. Model 4 - BERT produced an F1 score of 1.00 (train) and 0.72 (test)

BERT was the only model to don't accomplish at least 0.85 in testing phase as F1 score but this depended on the fact that my BERT model was obtained just on a 500 sample (since working on CPU), I am pretty sure that training the model on the entire dataset the threshold is going to get reached and probably this model can accomplish even better results compared to the others.
