
# Introduction
## Decision Tree
In computer science, decision tree learning uses a decision tree (as a predictive model) to go
from observations about an item (represented in the branches) to conclusions about the
item's target value (represented in the leaves). It is one of the predictive modeling
approaches used in statistics, data mining and machine learning. Tree models where the
target variable can take a discrete set of values are called classification trees; in these tree
structures, leaves represent class labels and branches represent conjunctions of features
that lead to those class labels. Decision trees where the target variable can take continuous
values (typically real numbers) are called regression trees. In decision analysis, a decision
tree can be used to visually and explicitly represent decisions and decision making. In data
mining, a decision tree describes data (but the resulting classification tree can be an input
for decision making). This page deals with decision trees in data mining.
# Dataset
## Classification Trees with Numerical Features (two datasets)
- Iris: has three classes and the task is to accurately predict one of the three subtypes of
the Iris flower given four different physical features. These features include the length
and width of the sepals and the petals. There are a total of 150 instances with each
class having 50 instances.
- Spambase: is a binary classification task and the objective is to classify email
messages as being spam or not. To this end the dataset uses seven text-based
features to represent each email message. There are about 4600 instances.
Since both datasets have continuous features you will implement decision trees that have
binary splits. For determining the optimal threshold for splitting you will need to search over
all possible thresholds for a given feature (refer to class notes and discussion for an efficient
search strategy). Use information gain to measure node impurity in your implementation.
