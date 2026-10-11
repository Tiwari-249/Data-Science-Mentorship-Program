# Machine Learning — CampusX DSMP

This folder contains Machine Learning fundamentals, regression, optimization, feature selection, regularization, classification, dimensionality reduction, ensemble learning, gradient boosting, feature engineering, and unsupervised learning from the CampusX Data Science Mentorship Program (DSMP).

## Table of Contents

- [Week 23: Linear Regression](#week-23-linear-regression)
- [Week 24: Gradient Descent](#week-24-gradient-descent)
- [Week 25: Regression Analysis](#week-25-regression-analysis)
- [Week 26: Feature Selection](#week-26-feature-selection)
- [Week 27: Regularization](#week-27-regularization)
- [Week 28: K-Nearest Neighbors](#week-28-k-nearest-neighbors)
- [Week 29: Principal Component Analysis](#week-29-pca)
- [Week 30: Model Evaluation and Selection](#week-30-model-evaluation--selection)
- [Week 31: Naive Bayes](#week-31-naive-bayes)
- [Week 32: Logistic Regression](#week-32-logistic-regression)
- [Week 33: Support Vector Machines](#week-33-support-vector-machines-svm)
- [Week 34: Decision Trees](#week-34-decision-trees)
- [Week 35: Ensemble Methods](#week-35-ensemble-methods)
- [Week 36: Gradient Boosting](#week-36-gradient-boosting)
- [XGBoost](#xgboost)
- [Feature Engineering](#feature-engineering)
- [Unsupervised Learning](#unsupervised-learning)
- [Learning Objectives](#learning-objectives)
- [Technologies Covered](#technologies-covered)

---

## Week 23: Linear Regression

### 1. Session 48: Introduction to Machine Learning

#### Machine Learning Fundamentals

- History and definition of Machine Learning
- Types of Machine Learning:
  - Supervised Learning
  - Unsupervised Learning
  - Semi-supervised Learning
  - Reinforcement Learning
- Batch/Offline Machine Learning
- Disadvantages of Batch Learning
- Online Machine Learning
- Importance and applications of Online Learning
- When and how to use Online Learning
- Learning Rate
- Out-of-Core Learning
- Disadvantages of Online Learning
- Batch Learning vs. Online Learning
- Instance-Based Learning
- Model-Based Learning
- Instance-Based vs. Model-Based Learning

#### Challenges in Machine Learning

- Data collection
- Insufficient or labelled data
- Non-representative data
- Poor-quality data
- Irrelevant features
- Overfitting and underfitting
- Offline learning
- Computational cost

#### Machine Learning Workflow

- Machine Learning Development Lifecycle
- Different job roles in Data Science
- Framing a Machine Learning problem
- Planning a Data Science project

### 2. Session 49: Simple Linear Regression

- Introduction and types of Linear Regression
- Simple Linear Regression
- Intuition behind Simple Linear Regression
- Code implementation
- Finding slope and intercept (\(m\) and \(b\))
- Implementing Simple Linear Regression from scratch

#### Regression Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared score
- Adjusted R-squared score

### 3. Session 50: Multiple Linear Regression

- Introduction to Multiple Linear Regression (MLR)
- MLR implementation
- Mathematical formulation of MLR
- Error function of MLR
- Minimizing error
- Further study of the error function
- Implementing MLR from scratch

### 4. Session: Optimization — The Big Picture

- Mathematical functions
- Multivariable functions
- Parameters in a function
- Machine Learning models as mathematical functions
- Parametric vs. non-parametric Machine Learning models
- Linear Regression as a parametric model
- Loss functions
- Selecting an appropriate loss function
- Calculating parameters using a loss function
- Convex and non-convex loss functions
- Gradient Descent
- Gradient Descent with multiple parameters
- Problems faced during optimization
- Other optimization techniques

### 5. Session: Differential Calculus

- Introduction to differentiation
- Derivative of a constant
- Differentiation cheat sheet
- Power Rule
- Sum Rule
- Product Rule
- Quotient Rule
- Chain Rule
- Partial differentiation
- Higher-order derivatives
- Matrix differentiation

---

## Week 24: Gradient Descent

### 1. Session 51: Gradient Descent from Scratch

- What is Gradient Descent?
- Intuition behind Gradient Descent
- Mathematical formulation
- Implementation from scratch
- Visualization
- Effect of learning rate
- Adding the slope parameter \(m\) to the equation
- Effect of the loss function
- Effect of data on Gradient Descent

### 2. Session 52 — Part 1: Batch Gradient Descent

- Types of Gradient Descent
- Mathematical formulation
- Implementation from scratch

### 3. Session 52 — Part 2: Stochastic Gradient Descent

- Problems with Batch Gradient Descent
- Introduction to Stochastic Gradient Descent
- Implementation from scratch
- Time comparison
- Visualization
- When to use Stochastic Gradient Descent
- Learning schedules
- Scikit-learn documentation

### 4. Session 52 — Part 3: Mini-Batch Gradient Descent

- Introduction to Mini-Batch Gradient Descent
- Code implementation
- Visualization

### 5. Doubt Clearance: Linear Regression

- Revision and doubt resolution for Linear Regression and Gradient Descent

---

## Week 25: Regression Analysis

### 1. Session: Regression Analysis — Part 1

- What is Regression Analysis?
- Why Regression Analysis is required
- Statistical connections with Regression Analysis
- Inference vs. prediction
- Linear Regression using Statsmodels
- Total Sum of Squares (TSS)
- Residual Sum of Squares (RSS)
- Explained Sum of Squares (ESS)
- Degrees of freedom
- F-statistic and Prob(F-statistic)

### 2. Session: Regression Analysis — Part 2

- F-test for overall significance
- R-squared and goodness of fit
- Adjusted R-squared
- T-statistic
- Confidence intervals for coefficients

### 3. Session: Polynomial Regression

- Why Polynomial Regression is needed
- Mathematical formulation of Polynomial Regression
- Polynomial Regression using Python

### 4. Session: Assumptions of Linear Regression

- Linearity
- Normality of residuals
- Homoscedasticity
- No autocorrelation
- No or little multicollinearity
- Consequences of violated assumptions
- Checking each assumption
- Handling failed assumptions
- Standard Error

### 5. Session 53: Multicollinearity

- What is multicollinearity?
- When multicollinearity becomes a problem
- Mathematical understanding of multicollinearity
- Perfect and non-perfect multicollinearity
- Types of multicollinearity
- Detecting multicollinearity
- Correlation
- Variance Inflation Factor (VIF)
- Condition Number
- Removing multicollinearity

---

## Week 26: Feature Selection

### 1. Session 54: Feature Selection — Part 1

- What is Feature Selection?
- Why Feature Selection is needed
- Types of Feature Selection

#### Filter-Based Feature Selection

- Duplicate features
- Variance Threshold
- Correlation
- ANOVA
- Chi-square
- Advantages and disadvantages

### 2. Session 55: Feature Selection — Part 2

#### Wrapper Methods

- Introduction to wrapper methods
- Types of wrapper methods
- Exhaustive Feature Selection / Best Subset Selection
- Sequential Backward Selection / Elimination
- Sequential Forward Selection
- Advantages and disadvantages

### 3. Session: Feature Selection — Part 3

#### Embedded Methods

- Linear Regression-based feature selection
- Tree-based models
- Regularized models
- Recursive Feature Elimination (RFE)
- Advantages and disadvantages

---

## Week 27: Regularization

### 1. Session: Bias-Variance Trade-off

- Why Bias and Variance are important
- Expected value and variance
- Mathematical understanding of bias and variance
- Bias-Variance decomposition
- Visual representation
- Intuition and analogy
- Code examples

### 2. Session: Introduction to Regularization

- What is Regularization?
- Why Regularization is needed
- When to use Regularization

### 3. Ridge Regression — Part 1

- Types of Regularization
- Geometric intuition
- Scikit-learn implementation

### 4. Ridge Regression — Part 2

- Ridge Regression for two-dimensional data
- Ridge Regression for n-dimensional data
- Implementation from scratch

### 5. Ridge Regression — Part 3

- Ridge Regression using Gradient Descent

### 6. Ridge Regression — Part 4

- Five key understandings
- Effect of Regularization on coefficients
- Greater impact on larger coefficients
- Bias-Variance trade-off
- Contour plots
- Why it is called Ridge Regression

### 7. Lasso Regression

- Intuition behind Lasso Regression
- Code implementation
- Key concepts of Lasso Regression

### 8. Session: Why Lasso Regression Creates Sparsity

- Understanding sparsity in Lasso Regression

### 9. ElasticNet Regression

- Introduction and intuition
- Code implementation

### 10. Doubt Clearance: Regularization

- Revision and doubt resolution for Regularization

---

## Week 28: K-Nearest Neighbors

### 1. Session: K-Nearest Neighbors — Part 1

- KNN intuition
- Code examples
- Selecting the value of K
- Decision surface
- Overfitting and underfitting in KNN
- Limitations of KNN

### 2. Session: Implementing KNN from Scratch

- Coding K-Nearest Neighbors from scratch

### 3. Session: Decision Boundaries

- Drawing decision boundaries for classification problems

### 4. Session: Advanced KNN — Part 2

- KNN Regressor
- KNN hyperparameters
- Weighted KNN
- Euclidean and Manhattan distances
- Time and space complexity
- KD-Tree

### 5. Session: Classification Metrics — Part 1

- Accuracy
- Accuracy in multiclass classification
- What makes a good accuracy score?
- Problems with accuracy
- Confusion matrix
- Type I error
- Type II error
- Confusion matrix for multiclass classification
- Situations where accuracy is misleading

### 6. Session: Classification Metrics — Part 2

- Precision
- Recall
- F1-score
- Multiclass precision and recall
- Multiclass F1-score

---

## Week 29: Principal Component Analysis (PCA)

### 1. Session: Curse of Dimensionality

- Introduction to the Curse of Dimensionality

### 2. PCA — Part 1

- Introduction to PCA
- Geometric intuition
- Importance of variance

### 3. PCA — Part 2

- Mathematical formulation of PCA
- Covariance and covariance matrix
- Matrices as linear transformations
- Eigenvectors and eigenvalues
- Step-by-step solution of PCA
- Transforming data points
- Implementing PCA step by step in Python

### 4. PCA — Part 3

- Practical example using the MNIST dataset
- PCA using Scikit-learn
- Visualization
- Explained variance
- Finding the optimal number of principal components
- Situations where PCA does not work well

### 5. Session: Eigenvectors and Eigenvalues

- Introduction to matrices
- Eigenvectors and eigenvalues
- Intuition using the axis of rotation
- Calculating eigenvectors and eigenvalues
- Properties of eigenvectors and eigenvalues
- Eigenvectors in PCA

### 6. Session: Eigen Decomposition and PCA Variants

- Types of PCA variants
- Special matrices:
  - Diagonal Matrix
  - Orthogonal Matrix
  - Symmetric Matrix
- Matrix-as-linear-transformation visualization
- Matrix composition
- Matrix decomposition
- Eigen decomposition
- Spectral decomposition of symmetric matrices
- Advantages of eigen decomposition
- Kernel PCA
- Kernel PCA implementation

### 7. Session: Singular Value Decomposition (SVD)

- Intuition behind non-square matrices
- Rectangular diagonal matrices
- What is SVD?
- Applications of SVD
- Mathematical intuition of SVD
- Relationship between SVD and eigen decomposition
- Geometric intuition
- Calculating SVD
- SVD in PCA

---

## Week 30: Model Evaluation and Selection

### 1. Session: ROC Curve in Machine Learning

- ROC curve and ROC-AUC
- Requirements for ROC-AUC
- Confusion matrix
- True Positive Rate (TPR)
- False Positive Rate (FPR)
- Different combinations of TPR and FPR

### 2. Session: Cross-Validation

- Why Cross-Validation is needed
- Hold-out approach
- Problems with the hold-out approach
- Why the hold-out approach is used
- Introduction to Cross-Validation

#### Leave-One-Out Cross-Validation (LOOCV)

- Advantages
- Disadvantages
- When to use

#### K-Fold Cross-Validation

- Advantages
- Disadvantages
- When to use

#### Stratified K-Fold Cross-Validation

- Introduction and use

### 3. Session: Data Leakage

- What is Data Leakage?
- Problems caused by Data Leakage
- Ways Data Leakage occurs
- Detecting Data Leakage
- Preventing Data Leakage
- Validation set

### 4. Session: Hyperparameter Tuning

- Parameter vs. hyperparameter
- Meaning of the term "hyperparameter"
- Requirements for hyperparameter tuning
- Grid Search CV
- Randomized Search CV
- Improving hyperparameter search

---

## Week 31: Naive Bayes

### 1. Crash Course on Probability — Part 1

- Five important probability terms:
  - Random Experiment
  - Trials
  - Outcome
  - Sample Space
  - Event
- Examples of probability terminology
- Types of events
- Definition of probability
- Empirical vs. theoretical probability
- Random variables
- Probability distributions of random variables
- Mean of random variables
- Variance of random variables

### 2. Crash Course on Probability — Part 2

- Venn diagrams
- Contingency tables
- Joint probability
- Marginal probability
- Conditional probability
- Intuition behind conditional probability
- Independent, dependent, and mutually exclusive events
- Bayes' Theorem

### 3. Session 1: Naive Bayes

- Intuition behind Naive Bayes
- Mathematical formulation
- Handling numerical data
- Handling non-Gaussian data
- Naive Bayes for textual data

### 4. Session 2: Naive Bayes

- Underflow in computing
- Log probabilities
- Laplace additive smoothing
- Bias-Variance trade-off
- Types of Naive Bayes:
  - Gaussian Naive Bayes
  - Categorical Naive Bayes
  - Multinomial Naive Bayes

### 5. Session 3: Naive Bayes and Probability Distributions

- Probability distributions used in Naive Bayes:
  - Bernoulli Distribution
  - Binomial Distribution
  - Categorical / Multinoulli Distribution
  - Multinomial Distribution
- Why these distributions are needed
- Categorical Naive Bayes
- Bernoulli Naive Bayes
- Multinomial Naive Bayes
- Out-of-Core Naive Bayes

### 6. End-to-End Project: Email Spam Classifier

- Building an end-to-end email spam classification project

---

## Week 32: Logistic Regression

### 1. Session 1: Logistic Regression

- Introduction to Logistic Regression
- Basic geometry
- Classification problem
- Basic classification algorithm
- Updating the basic algorithm
- Sigmoid function
- Maximum Likelihood
- Log Loss
- Gradient Descent
- Summary

### 2. Session: Multiclass Classification Using Logistic Regression

- What is multiclass classification?
- How Logistic Regression handles multiclass problems
- One-vs-Rest (OVR) approach
- OVR intuition and implementation
- Softmax Logistic Regression
- Softmax function
- Softmax implementation
- Choosing between OVR and Softmax
- Practice tasks

### 3. Session: Maximum Likelihood Estimation (MLE)

- Recap and examples
- Coin toss example
- Drawing balls from a bag
- Normal Distribution example
- Probability vs. likelihood
- Maximum Likelihood Estimation
- MLE for Normal Distribution
- MLE in Machine Learning
- MLE in Logistic Regression

### 4. Session 3: Logistic Regression — Advanced Concepts

- Maximum Likelihood in Logistic Regression
- FAQs about MLE
- Is MLE applicable to all Machine Learning algorithms?
- Relationship between MLE and loss functions
- Why loss functions are used instead of directly maximizing likelihood
- Why MLE is important
- Assumptions of Logistic Regression
- Odds and log-odds
- Alternative interpretation of Logistic Regression
- Polynomial features
- Regularization in Logistic Regression

### 5. Session: Logistic Regression Hyperparameters

- Logistic Regression hyperparameters

---

## Week 33: Support Vector Machines (SVM)

### 1. SVM — Part 1: Hard Margin SVM

- Introduction to SVM
- Maximum Margin Classifier
- Support vectors
- Mathematical formulation
- Solving the optimization problem
- Prediction
- Coding example
- Problems with Hard Margin SVM

### 2. SVM — Part 2: Soft Margin SVM

- Limitations of Hard Margin SVM
- Slack variables
- Soft Margin SVM
- The C parameter
- Bias-Variance trade-off
- Code example
- Relationship between SVM and Logistic Regression

### 3. Session: Constrained Optimization and Kernels

- Problems with SVC
- Intuition behind kernels
- Kernel coding examples
- Types of kernels
- Why it is called the Kernel Trick
- Mathematics of SVM

### 4. Session: SVM Dual Problem

- SVM in n dimensions
- Constrained optimization problems
- Karush-Kuhn-Tucker (KKT) conditions
- Concept of duality
- SVM dual problem
- Derivation of the dual problem
- Observations

### 5. Session: Mathematics Behind SVM Kernels

- SVM dual formulation
- Similarity perspective
- Kernel SVM
- Polynomial kernel and the Kernel Trick
- Other polynomial terms
- Radial Basis Function (RBF) kernel
- Local decision boundaries
- Effect of Gamma
- Relationship between RBF and polynomial kernels
- Custom kernels:
  - String Kernel
  - Chi-Square Kernel
  - Intersection Kernel
  - Hellinger's Kernel
  - Radial Basis Function Network (RBFN) Kernel
  - Spectral Kernel

---

## Week 34: Decision Trees

### 1. Session 1: Decision Trees

- Introduction to Decision Trees
- Intuition behind Decision Trees
- Decision Tree terminology
- CART algorithm for classification
- Splitting categorical features
- Splitting numerical features
- Gini impurity
- Geometric intuition of Decision Trees

### 2. Session 2: Decision Trees

- CART for regression
- Geometric intuition of CART
- How predictions are made
- Advantages and disadvantages of Decision Trees
- Real Estate project discussion

### 3. Session 3: Decision Trees

- Feature importance
- Overfitting in Decision Trees
- Why overfitting occurs
- Unnecessary nodes
- Pruning and its types:
  - Pre-pruning
  - Post-pruning
  - Cost-complexity pruning

### 4. Session: Decision Tree Visualization

- Decision Tree visualization using `dtreeviz`
- Coding demonstration

---

## Week 35: Ensemble Methods

### 1. Introduction to Ensemble Learning

- Intuition behind Ensemble Learning
- Types of Ensemble Learning
- Why Ensemble Learning works
- Benefits of Ensemble Learning
- When to use Ensemble Learning

### 2. Bagging — Part 1: Introduction

- Core idea of Bagging
- Why Bagging is used
- When to use Bagging
- Code demonstration

### 3. Bagging — Part 2: Classifier

- Intuition using a demonstration application
- Bagging Classifier implementation

### 4. Bagging — Part 3: Regressor

- Core idea of Bagging Regression
- Intuition using a demonstration application
- Bagging Regressor implementation

### 5. Random Forest — Session 1

- Introduction to Random Forest
- Bagging
- Random Forest intuition
- Why Random Forest works
- Bagging vs. Random Forest
- Feature importance

### 6. Random Forest — Session 2

- Why Ensemble Techniques work
- Random Forest hyperparameters
- Out-of-Bag (OOB) score
- Extremely Randomized Trees
- Advantages and disadvantages of Random Forest

---

## Week 36: Gradient Boosting

### 1. Gradient Boosting — Session 1

- Introduction to Boosting
- What is Gradient Boosting?
- Understanding how, what, and why Gradient Boosting works

### 2. Gradient Boosting — Session 2

- How Gradient Boosting works
- Intuition behind Gradient Boosting
- Function space vs. parameter space
- Direction of loss minimization
- Updating the function
- Iterative model building
- Alternative perspective on Gradient Boosting
- Gradient Boosting vs. Gradient Descent

### 3. Gradient Boosting — Session 3: Classification — Part 1

- Classification vs. regression
- Prediction in Gradient Boosting classification

### 4. Gradient Boosting for Classification — Part 2

- Geometric intuition

### 5. Gradient Boosting for Classification — Part 3: Mathematical Formulation

- Step 0: Loss function
- Step 1: Minimizing the loss function to obtain \(F_0(x)\)
- Step 2:
  - Pseudo-residuals
  - Training a regression tree
  - Computing Lambda for all leaf nodes
  - Updating the model
- Step 3: Final model
- Log-odds vs. probability

---

## XGBoost

### 1. Introduction to XGBoost

- Introduction to Extreme Gradient Boosting
- Features of XGBoost:
  - Performance
  - Speed
  - Flexibility

### 2. XGBoost for Regression

- Regression problem statement
- Step-by-step mathematical calculations

### 3. XGBoost for Classification

- Classification problem statement
- Step-by-step mathematical calculations

### 4. Complete Mathematics of XGBoost

- Prerequisites
- Boosting as an additive model
- XGBoost loss function
- Deriving the objective function
- Problems with the objective function and their solutions
- Taylor series
- Applying Taylor series
- Simplification
- Output value for regression
- Output value for classification
- Derivation of similarity score
- Final similarity score calculation

### 5. Advanced XGBoost: Revisiting the Fundamentals

- Supervised Machine Learning
- Stagewise Additive Modelling
- XGBoost objective function

### 6. XGBoost Regularization

- Ways to reduce overfitting in XGBoost
- Gamma
- Maximum depth
- Number of estimators
- Early stopping
- Shrinkage
- Minimum child weight
- Lambda and Alpha
- Subsample
- Column subsampling

### 7. XGBoost Optimization

- Reasons for slow boosting algorithms
- Exact greedy split finding
- Approximate split finding
- Optimization improvements:
  - Reducing the number of splits
  - Calculation of G and H
  - Parallel processing
  - Cache storage
  - Quantile sketch
  - Weighted quantile sketch

### 8. Handling Missing Values in XGBoost

- How XGBoost handles missing values

---

## Feature Engineering

### 1. Session: Encoding Categorical Features — Part 1

#### Feature Engineering Fundamentals

- Feature Engineering roadmap
- What is Feature Encoding?

#### Ordinal Encoding

- Ordinal Encoding
- Python code examples
- Handling rare categories

#### Label Encoding

- Label Encoding
- Scikit-learn `LabelEncoder`
- Code examples

#### One-Hot Encoding

- One-Hot Encoding (OHE)
- Scikit-learn `OneHotEncoder`
- Handling unknown categories
- `LabelBinarizer`

### 2. Session: Scikit-learn ColumnTransformer and Pipeline

- What is `ColumnTransformer`?
- Implementing `ColumnTransformer`
- One-Hot Encoding with ColumnTransformer
- Ordinal Encoding with ColumnTransformer
- Scikit-learn Pipelines
- Applying multiple transformations in a pipeline:
  - Missing-value imputation
  - Categorical encoding
  - Handling rare categories
  - Feature scaling
  - Feature selection
  - Model building
  - Prediction

### 3. Session: Scikit-learn Deep Dive

- Estimators
- Custom estimators
- Mixins
- Transformers
- Custom transformers
- Composite transformers
- ColumnTransformer
- Feature Union
- Pipeline

### 4. Session: Encoding Categorical Features — Part 2

- Count Encoding
- Frequency Encoding
- CountEncoder library
- Binary Encoding
- Target Encoding

### 5. Session: Discretization — Part 1

- Remaining categorical encoding topics
- Weight of Evidence
- Choosing the appropriate encoder
- What is Discretization?
- Why Discretization is useful:
  - Reducing overfitting
  - Handling non-linear relationships
  - Handling outliers
  - Better interpretability
  - Model compatibility
- Disadvantages of Discretization

### 6. Session: Discretization — Part 2

- Types of Discretization:
  - Uniform Binning
  - Quantile Binning
  - K-Means Binning
  - Decision Tree-based Binning
  - Custom Binning
  - Threshold Binning (Binarization)

### 7. Session: Handling Missing Data — Part 1

- Missing values
- The `missingno` library
- Why missing values occur
- Types of missing values
- Impact of missing values on Machine Learning models
- Techniques for handling missing values:
  - Removing missing values
  - Imputation
- Removing missing data

### 8. Session: Handling Missing Data — Part 2

- Removing missing values
- Missing Indicator
- When to use and when not to use a Missing Indicator
- Simple Imputer:
  - Mean
  - Median
  - Most Frequent
  - Constant
- Selecting an appropriate imputation technique

### 9. Session: Handling Missing Data — Multivariate Imputation

- NaN Euclidean distance
- KNN Imputer
- KNN Imputer code and hyperparameters
- When to use and when not to use KNN Imputation
- Advantages and disadvantages of KNN Imputation
- Iterative Imputer
- Iterative Imputer code and parameters
- When to use and when not to use Iterative Imputation
- Advantages and disadvantages of Iterative Imputation
- Comparing different imputation techniques

### 10. Session: Feature Scaling — Part 1

- What is Feature Scaling?
- Why Feature Scaling is needed
- Algorithms affected by unscaled features
- Algorithms not affected by feature scaling
- Standardization

### 11. Session: Feature Scaling — Part 2

- Min-Max Scaling
- Standardization vs. Min-Max Scaling
- Robust Scaler
- Max Absolute Scaler
- L1 and L2 Normalization
- Comparing feature-scaling techniques

### 12. Session: Outlier Detection — Part 1

- What are outliers?
- Types of outliers
- Impact of outliers
- Handling outliers
- Outlier detection techniques

#### Univariate Outlier Detection

- Z-score
- IQR and boxplots
- Problems with univariate techniques

#### Multivariate Outlier Detection

- Isolation Forest

### 13. Session: Outlier Detection — Part 2

- Isolation Forest
- Calculation of anomaly score
- Outlier detection using KNN
- Local vs. global outliers
- Local Outlier Factor (LOF)

### 14. Session: Outlier Detection — Part 3

- Local Outlier Factor (LOF)
- DBSCAN code and visualization
- Accessing model accuracy
- Choosing an appropriate outlier detection algorithm

### 15. Session: Feature Transformation

- Why feature transformations are needed
- What are Feature Transformations?
- Problems after transformation
- Log Transformation
- Algorithms that benefit from Log Transformation
- When to use and when not to use Log Transformation
- Square Root Transformation
- Reciprocal Transformation
- Boston Housing Price case study
- Square Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation

---

## Unsupervised Learning

### 1. K-Means Clustering

#### Session 1: Introduction to K-Means

- Getting started with clustering
- Types of Machine Learning
- Applications of clustering
- Geometric intuition of K-Means
- Elbow Method for choosing the number of clusters
- Code example
- Limitations of the Elbow Method
- Assumptions of K-Means
- Limitations of K-Means

#### Session 2: K-Means Evaluation and Hyperparameters

- Recap and assignment solutions
- Silhouette score
- K-Means hyperparameters:
  - Number of clusters (\(k\))
  - Initialization method (K-Means++)
  - Number of initialization runs (`n_init`)
  - Maximum iterations (`max_iter`)
  - Tolerance (`tol`)
  - Algorithm
  - Random state
- K-Means++ initialization

#### Session 3: K-Means Advanced Concepts

- Mathematical formulation of K-Means (Lloyd's algorithm)
- Time and space complexity
- Mini-Batch K-Means
- Types of clustering:
  - Partitional Clustering
  - Hierarchical Clustering
  - Density-Based Clustering
  - Distribution/Model-Based Clustering

#### K-Means from Scratch

- Implementing K-Means algorithms from scratch in Python

### 2. Other Clustering Algorithms

#### Session: DBSCAN

- Why DBSCAN?
- Density-based clustering
- MinPts and Epsilon
- Core points, border points, and noise points
- Density-connected points
- DBSCAN algorithm
- Code implementation
- Limitations
- Visualization

#### Session: Hierarchical Clustering

- Need for alternative clustering methods
- Introduction to Hierarchical Clustering
- Algorithm
- Types of agglomerative clustering:
  - Minimum linkage (Single Link)
  - Maximum linkage (Complete Link)
  - Average Link
  - Ward Linkage
- Finding the ideal number of clusters
- Hyperparameters
- Code example
- Benefits and limitations

### 3. Gaussian Mixture Models (GMM)

#### Session 1: Introduction to GMM

- Motivation and introduction
- Geometric intuition
- Multivariate Normal Distribution
- Two-dimensional geometric intuition
- Expectation-Maximization (EM) algorithm
- Python implementation

#### Session 2: Advanced GMM

- Recap of the first session
- Covariance types:
  - Spherical
  - Diagonal
  - Full
  - Tied
- Choosing `n_components`
- Akaike Information Criterion (AIC)
- Bayesian Information Criterion (BIC)
- Likelihood formula for GMM
- Python implementation
- Why not use the Silhouette Score?
- Visualization
- Assumptions
- Advantages and disadvantages
- K-Means vs. GMM
- DBSCAN vs. GMM
- Applications of GMM

### 4. t-SNE — Part 1

- What is t-SNE?
- Why learn t-SNE?
- Geometric intuition
- Mathematical formulation
- Code implementation

### 5. t-SNE — Part 2

- Mathematical formulation
- Why probabilities are used instead of distances to calculate similarity
- Why Gaussian distributions calculate similarity in high dimensions
- Calculating variance for each Gaussian distribution
- Why the t-distribution is used in lower dimensions
- Code examples
- Hyperparameters:
  - Perplexity
  - Learning Rate
  - Number of Iterations
- Points of wisdom
- Advantages and disadvantages

### 6. Linear Discriminant Analysis (LDA)

- Introduction to supervised dimensionality reduction
- Algorithm explanation
- Maximizing between-class variance
- Applications in classification and visualization
- LDA vs. PCA: differences and similarities

### 7. Apriori Algorithm

- Introduction to association rule mining
- Key concepts:
  - Support
  - Confidence
  - Lift
- Algorithm steps
- Candidate generation
- Pruning
- Applications:
  - Market Basket Analysis
  - Recommender Systems

---

## Learning Objectives

- Understand supervised and unsupervised Machine Learning workflows.
- Implement Linear Regression and Gradient Descent from scratch.
- Evaluate regression and classification models using appropriate metrics.
- Perform regression analysis and test its assumptions.
- Apply feature selection and regularization techniques.
- Understand KNN, Naive Bayes, Logistic Regression, SVM, and Decision Trees.
- Apply PCA, eigen decomposition, and SVD for dimensionality reduction.
- Use cross-validation and hyperparameter tuning for model selection.
- Build ensemble models using Bagging, Random Forest, and Gradient Boosting.
- Understand and optimize XGBoost models.
- Perform feature encoding, scaling, transformation, and missing-value imputation.
- Detect and handle outliers.
- Apply K-Means, DBSCAN, Hierarchical Clustering, and GMM.
- Use t-SNE and LDA for dimensionality reduction.
- Understand association rule mining using the Apriori algorithm.

## Technologies Covered

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- XGBoost
- Jupyter Notebook / Google Colab
