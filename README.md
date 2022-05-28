#Machine Learning
Best trick to learn machine learning is just train a lot of data sets and create a lot of models, trust me It works better for me than reading books about it
# Types of Systems of Machine Learning
Supervised
Unsupervised
Semi-supervised
Reinforcement Learning
# Supervised Learning
Labeled Data

# Unsupervised Learning


# Reinforcement Learning
Environment -> Action -> Reward/Penalty

# Batch Learning
Use alot of data, launched without any learning.

# Online Learning
Opposite of Batch learning, system learns incrementally , providing the system available data as instances, system learns on the fly, speed can be known by the "learning rate"

# Instance based Learning
Simplest , does what the user did

# Model-based Learning
Learns from examples, makes predictions

# Bad , Insufficient Quantity of Training Data
Machine-learning systems require a lot of data to work effectively.

# Poor-Quality Data
Data set with errors and outliers -> Difficulty for the system to detect patterns

# Irrelevant Features
Relevant Data -> Machine Learning System Learns
Irrelevant Data -> Machine Learning System does not learn
not enough features in data -> Machine Learning System does not learn 
you get the point.

# Feature Engineering
Selection of features: selecting the most useful features
Extraction of features: combining existing features to provide mroe useful features
Creation of new features: creation of new features, based on data.
Features == transformations on input data that facilitate a downstream algorithm like a classifier.
# Testing
Divide data into 2 sets
Training set (Data that you use to train your model)
Testing set (Data that you use to test your model)
Generalized error(GR) is the rate of error of your model on the test set.
GR good = Model good
Recommended Divisions
80% data == training
20% data == testing

# Overfitting the Data
Machines work well with the training data, but they can not generalize it properly.
this is called Overfitting, it occurs when the model is too complex for the training data that is given to it.

# Solutions for Overfitting
More Data
Reduce the noise level
Choose a data set with fewer parameters

# Underfitting the Data
encountered when the model is very simple.

# Solutions for Underfitting
Select the model with more parameters, more powerful.
Feature Engineering 
Reduce the limits on your model

# Deeplearning with Pytorch
Data Source -(Sample Tensors)> MultiProcessDataLoading -> Batch Tensor -> (UntrainedModel) -> Training Loop(Distributed Training on multiple servers/gpus) -> Trained Model -> Production(ONNX, JIT, TORCHSCRIPT) -> CLOUD, Production Server
Before the last decade, Machine Learning == Heavily Reliant on "Feature Engineering" (Discussed Above).
 
