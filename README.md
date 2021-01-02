# MODELING ABSENTEEISM AT WORK DATASET USING SUPERVISED LEARNING
Machine Learning Models for Absenteeism at Work Dataset

## MACHINE LEARNING MODEL
In basic terms, Machine Learning (ML) is the process of training a piece of software, called a model, to make useful predictions using a data set. This predictive model can then serve up predictions about previously unseen data. We use these predictions to take action in a product; for example, the system predicts that a user will like a certain video, so the system recommends that video to the user.

Often, people talk about ML as having two paradigms, supervised, and unsupervised learning. For this repo, the paradigms of supervised learning use to modeling the Absenteeism at work Kaggle dataset.

### SUPERVISED LEARNING
A supervised learning algorithm takes labeled data and creates a model that can make predictions given new data.

These can be either a classification problem or a regression problem. In a classification problem, there might be test data consisting of photos of animals, each one labeled with its corresponding name. The model would be trained on this test data and then the model would be used to classify unlabeled animal photos with the correct name. In a regression problem, there is a relationship trying to be determined among many different variables. Usually, this takes place in the form of historical data being used to predict future quantities. An example of this would be predicting the future price of a stock based on past prices movements.

Following are some of the supervised modeling algorithms used in this repository.

#### DECISION TREE (CATEGORICAL TARGET VARIABLE)
A decision tree is a support tool with a tree-like structure that models probable outcomes, cost of resources, utilities, and possible consequences. Decision trees provide a way to present algorithms with conditional control statements. They include branches that represent decision-making steps that can lead to a favorable result.

A categorical variable decision tree includes categorical target variables that are divide into categories. For example, the categoric of data can be yes or no. That means that every stage of the decision process falls into one of them, and there are no in-betweens.

#### K-NEAREST NEIGHBORS (CATEGORICAL TARGET VARIABLE)
k-Nearest Neighbors (k-NN) is an algorithm that is useful for making classifications/predictions when there are potential non-linear boundaries separating classes or values of interest. Conceptually, k-NN examines the classes/values of the points around it (i.e., its neighbors). To determine the value of the significantly. The majority or average value will assign to interesting that point.

k-NN classification uses when predicting categorical outcomes, and k-NN regression when predicting continuous data.

#### RANDOM FOREST (CATEGORICAL TARGET VARIABLE)
Random Forest is a robust machine learning algorithms uses for a variety of tasks includes regression and classification. It is an ensemble method, meaning that a random forest model can improve the number of small decision trees, called estimators, which each produce their predictions. The random forest model combines the result of the estimators to pursue more accurately.

Random forests are very good for classification problems but are slightly less good at regression problems. In contrast to linear regression, a random forest regressor can't find the result of predict outside the range of its training data.

Random forests are also black boxes: in contrast to some more traditional machine learning algorithms, it is difficult to look inside a random forest classifier and understand what reason behind its decisions. Besides, they can be slow to train and run the models and produce large file sizes.

#### SUPPORT VECTOR MACHINE
Support Vector Machines (SVM) is a state-of-the-art algorithm with strong theoretical foundations based on the Vapnik-Chervonenkis theory. SVM has strong regularization properties. Regularization refers to the generalization of the model to new data.

##### SVM Classification 
SVM classification is base on the concept of decision planes that define decision boundaries. A decision plane is one that separates between a set of objects having different class memberships. SVM finds vectors ("support vectors") specifying a separator that provides a wide range of class separations.

SVM classification supports both binary and multiclass targets.

##### SVM Regression
SVM uses an epsilon-insensitive loss function to solve regression problems.

SVM regression tries to find a continuous function such that the maximum number of data points lie within the epsilon-wide insensitivity tube. Predictions falling within epsilon distance of the right target value not interpret as errors.

References 
- https://developers.google.com/machine-learning/problem-framing/cases
- https://medium.com/datadriveninvestor/what-is-machine-learning-55028d8bdd53
- https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning#introduction
- https://corporatefinanceinstitute.com/resources/knowledge/other/decision-tree/#:~:text=Categorical%20variable%20decision%20tree,there%20are%20no%20in%2Dbetweens.
- https://quantdev.ssri.psu.edu/sites/qdev/files/kNN_tutorial.html
- https://deepai.org/machine-learning-glossary-and-terms/random-forest
- https://docs.oracle.com/cd/E11882_01/datamine.112/e16808/algo_svm.htm#DMCON027


