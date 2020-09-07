# Filtering-Those-Pesky-Spam-Messages
In this project, we're going to study the practical side of the Naive Bayes algorithm by building a spam filter for SMS messages.

To classify messages as spam or non-spam, the computer:

1. Learns how humans classify messages.
2. Uses that human knowledge to estimate probabilities for new messages — probabilities for spam and non-spam.
3. Classifies a new message based on these probability values — if the probability for spam is greater, then it classifies the message as spam. Otherwise, it classifies it as non-spam (if the two probability values are equal, we may need a human to classify the message).

## The Data
The dataset was put together by Tiago A. Almeida and José María Gómez Hidalgo, which can be downloaded from [The UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection).
