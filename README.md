# Classifying-Trump-Tweets
It became known that while President Trump tweets from his Android phone to his twitter account, his staff members also tweet from their iPhones

# Task: Classify Trump tweets as being sent from iPhone or Android, to see who was actually tweeting

# Steps: 
1. Transformed the training data with a count-vectorizer. 
2. Plot the number of tweets by phone type, to acquire baseline accuracy of 60%.
3. Split the training data into training and validation sets and compared validation accuracy for various classification methods. 
4. Random Forest returned best validation accuracy, ~87%.
5. Tune hyperparameters, train model on entire transformed training set.
6. Final model attained 80% classification accuracy on test set tweets.
