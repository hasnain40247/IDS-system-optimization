# IDS-system-optimization

This project aims to provide useful insights about the
intrusion detection literature and is a good source for anyone
interested in applying one of the used optimization
algorithms in the field of intrusion detection. The dataset
used for the experiments carried out in this paper is a
standard benchmark dataset known as KDD Cup 99. It was
investigated and utilized to study the effectiveness of the
proposed method in this problem domain. We also look at
and analyse the other algorithms mentioned and compare the
results obtained. This process also should facilitate any study
in the field of Optimization Algorithms, not just for Intrusion
Detection but also any other neural network or machine
learning model in general. Here, we first look at Genetic
Algorithm (GA) as a tool capable of identifying malicious
connections in a computer network. Genetic Algorithms (GA)
are search algorithms which function based on the principles
of natural selection and genetics. GA develops a population
of initial individuals to a population of high quality
individuals, where each individual signifies a solution of the
problem to be solved. Particle swarm optimization (PSO) is
one of the bio-inspired algorithms and it is a simple one to
search for an optimal solution in the solution space. It is
different from other optimization algorithms in such a way
that only the objective function is needed and it is not
dependent on the gradient or any differential form of the
objective. It also has very few hyperparameters.

## Algorithms Used
#### 1. Naive Bayes
It's a classification method that uses Bayes' Theorem and
assumes predictor independence. A Naive Bayes classifier, to put it simply, assumes that the existence of one feature in
a class is independent to the presence of any other feature. It's a classification method that uses Bayes' Theorem and
assumes predictor independence. A Naive Bayes classifier, to put it simply, assumes that the existence of one feature in
a class is independent to the presence of any other feature.

#### 2. Decision Tree
A virus is a type of malware aimed to corrupt, erase or
moThe Decision Tree algorithm is part of the supervised
learning algorithms family. The decision tree approach, unlike other supervised learning algorithms, may also be
utilised to solve regression and classification issues. By
learning basic decision rules inferred from past data, the
purpose of employing a Decision Tree is to develop a
training model that can be used to predict the class or value
of the target variable (training data). We start at the root of
the tree when using Decision Trees to forecast a class label
for a record. The values of the root attribute and the record's
attribute are compared. We follow the branch that
corresponds to that value and go to the next node based on
the comparison. 
#### 3. Random Forest
Random forest is supervised machine learning algorithm
that is commonly used to solve classification and regression
issues. It creates decision trees from several samples, using
the majority vote for classification and the average for
regression. One of the most essential characteristics of the
Random Forest Algorithm is that it can handle data sets with
both continuous and categorical variables, as in regression
and classification. For classification difficulties, it produces
superior results
#### 4. XGBoost
Extreme Gradient Boosting (XGBoost) is a distributed
gradient-boosted decision tree (GBDT) machine learning
toolkit that is scalable. It is the top machine learning library
for regression, classification, and ranking tasks, and it
includes parallel tree boosting.
####5. Ensemble Algorithm
It is an ensemble algorithm combining Naive Bayes, Decision Tree, Random Forest and Xgboost giving the
hierarchy of classification and gradient boost by Xgboost
along with Random Forest in the lowest layer of execution
path.
#### 6. Conditional Variational Autoencoder (CVAE)
The CVAE is a conditional directed graphical model in
which the input observations modulate the prior on Gaussian
latent variables, which produce the outputs. It has been
programmed to optimise conditional marginal log-likelihood. 
#### 7. LightBGM
It is a gradient boosting framework that makes use of tree
based learning algorithms. While other algorithms trees
grow horizontally, LightGBM algorithm grows vertically
meaning it grows leaf-wise and other algorithms grow level- wise. LightGBM chooses the leaf with large loss to grow. It
can lower down more loss than a level wise algorithm when
growing the same leaf. 
#### 8. Particle Swarm Optimizatin (PSO)
Particle swarm optimization (PSO) is one of the bio inspired algorithms and it is a simple one to search for an
optimal solution in the solution space. It is different from
other optimization algorithms in such a way that only the
objective function is needed and it is not dependent on the
gradient or any differential form of the objective. It also has
very few hyper-parameters.

#### 9. Genetic Algorithm
Genetic Algorithm was developed in order to be applied
in a computer network. Genetic algorithms mimic the
principles involved in evolutionary sciences, such as the
concept of natural selection. This method should be able to
identify and estimate the differences between the behavior of
the unauthorized connection and normal connection using a
proposed fitness (objective) function, the better the fitness
valIt begins with generating 100 chromosomes randomly. A
chromosome in this context is a set of parameters that define
a proposed solution to the problem that the genetic algorithm
is trying to solve. Next, an attack recognition between
generated chromosomes and training data takes place. This is
followed by applying the fitness function to measure fitness
value. A fitness function simply defined is a function that
takes the solution as input and produces the suitability of the
solution as the output.ue, the better the solution, much like
how the survival of the fittest works in nature.


![image](https://user-images.githubusercontent.com/52504037/211485381-5e8aa7a0-e062-42e7-b779-896d81c279b8.png)
