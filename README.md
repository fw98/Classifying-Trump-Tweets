# Classifying-Trump-Tweets
It became known that while President Trump tweets from his Android phone to his twitter account, his staff members also tweet from their iPhones
# Task: Classify Trump tweets as being sent from iPhone or Android, to see who was actually tweeting

# Steps: 
I first transformed the training data with a count-vectorizer. I then split the training data into training and validation sets and compared validation accuracy for various classification methods. After choosing the best method, I tuned hyperparameters and achieved 80% accuracy on the actual test set of tweets
