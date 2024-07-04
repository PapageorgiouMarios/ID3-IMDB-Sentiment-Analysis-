# ID3-IMDB-Sentiment-Analysis-
Use Custom ID3 Machine Learning Algorithm to predict the sentiment of each comment as positive(1) or negative(0)

The ID3 (Iterative Dichotomiser 3) algorithm is used for constructing decision trees in machine learning problems. Starting with all the training data, it selects the feature that makes the greatest discriminative distinction. It creates a node in the tree with this feature and splits the data accordingly. The process is repeated for each subset, proceeding in depth, until a termination criterion is met, such as complete classification or reaching a predetermined depth. The final decision tree can be used to classify new data based on their features.

For our database we will be using the IMDB movie reviews database from Tensorflow keras library (tf.keras.datasets.imdb).
