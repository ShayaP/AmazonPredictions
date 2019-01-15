# AmazonPredictions
<h3>Description:</h3>
This model can predict Categories of Amazon items based on reviews and whether a user would purchase an item based on their purchase history.

<h3>For task 1:</h3> sentiment analysis was used on all items in the dataset to create feature vectors based on tf-idf scores of each word. These words were used to train a multi-class SVM to predict categories of items.

<h3>For task 2:</h3> A similarity score was used to determine if two items were similar or not, since a user is more likely to purchase an item that is similar to another item.

<h3>Scores:</h3>
For task 1, the multi-class SVM achieved an accuracy of 90.52% on the validation set and little more than 88% on the test set.

For task 2, the model achieved an accuracy of 51.64% on the validation and almost 50% on the test set.
