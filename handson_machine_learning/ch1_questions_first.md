# 1

Machine learning is the science of teaching software to make decisions based on data

# 2

Machine learning shines in:
  - Image recognition
  - problems that have lots of rules
  - situations where you are trying to gain insight from abundant data
  - fluctuating environments

# 3

A labeled training set is a training set used in supervised learning where the data is "labeled" with the correct outcome

# 4
Two common supervised tasks are object recognition (classification) and line itting (regression)

# 5

Four unsupervised tasks are:

- clustering data features
- visualization (2D or 3D)
- anomaly detection (ie credit card fraud type algorithms)
- feature extraction

# 6

You would use a conditioning algorithm to teach a robot to walk on different terrains.  (Reinforcement learning) This is an unsupervised learning method

# 7

To separate your customers into groups, you would use a clustering algorithm

# 8

Spam detection is a form of supervised learning.  It depends on knowing what emails are classified as spam by users, and then using a measure of similarity to identify new emails as spam.  However, it will still depend on user intervenetion to know if the new emails are spam or not

# 9

An online learning system is an unsupervised system where the learning takes place in small batches.  This means it can train while the system is live.  New training is fast(er) and cheap(er).

# 10

Out-of-core learning is learning where all of the training data can't fit into the machine's main memory. It is online learning.

# 11

Association rule learning and anomaly attention both rely on similarity measures.

# 12

A hyperparamater is a constant parameter for a learning algorithm. It is set prior to training the model and used to regularize the fit of a model.  A model parameter is dependent on the data itself.  All model parameters are chosen by using a fitness function.

# 13

Model based learning algorithms look for a mathematical function that accurately predicts the correct result based on input parameters.

# 14

Four main challenges in machine learning:

1. Overfitting to training data
2. Underfitting training data
3. Determining the correct model
4. Escaping training and sampling bias

# 15

If your model performs well on the training data but poorly elswhere, you've overfit your training data. Three possible solutions:

1. Split your training data into 80% training, 20% validation and make sure that it does well on both sets of data before continuing.
2. Get more training data
3. Introduce a hyperparameter to regularize the dat

# 16

A test set is a subset of the training data that is set aside to...test the model that has been constructed from the training data. It's useful to see if you have overfit your model to your training data.

# 17

A validation set is a subset of the training data that is used to test the efficacy of multiple models.  The model with the best fit is decided by comparing against the validation data. It is useful as a substep before the test set to use to compare different machine learning systems.

# 18

If you tune hyperparameters to the test set, you may find that you have overfit your model to the test set!

# 19

Cross validation is the process of splitting the training set into complementary sets.  Different models are trained used different subsets and validated using the remaining subsets.  Once a model has been selected, it is trained against the full training set.  This allows you to avoid wasting too much training data for validation.

