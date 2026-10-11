# Statistics, Probability and Linear Algebra — CampusX DSMP

This folder contains descriptive statistics, probability distributions, inferential statistics, hypothesis testing, and linear algebra concepts from the CampusX Data Science Mentorship Program (DSMP).

## Table of Contents

- [Week 17: Descriptive Statistics](#week-17-descriptive-statistics)
- [Week 18: Descriptive Statistics Continued](#week-18-descriptive-statistics-continued)
- [Week 19: Probability Distributions](#week-19-probability-distributions)
- [Week 20: Inferential Statistics](#week-20-inferential-statistics)
- [Week 21: Hypothesis Testing](#week-21-hypothesis-testing)
- [Week 22: Linear Algebra](#week-22-linear-algebra)
- [Learning Objectives](#learning-objectives)
- [Technologies Covered](#technologies-covered)

---

## Week 17: Descriptive Statistics

### 1. Session 38: Descriptive Statistics — Part 1

- What is Statistics?
- Types of Statistics
- Population vs. Sample
- Types of Data
- Measures of Central Tendency
- Measures of Dispersion
- Coefficient of Variation
- Graphs for Univariate Analysis
- Frequency Distribution Tables
- Graphs for Bivariate Analysis
- Categorical vs. Categorical Analysis
- Numerical vs. Numerical Analysis
- Categorical vs. Numerical Analysis

### 2. Session: Datetime in SQL

#### Advanced SQL-Based EDA

- Remaining topics of EDA using SQL
- Numerical vs. categorical analysis
- Handling missing values
- PPI and price bracket analysis
- One-hot encoding

#### Datetime in SQL

- Temporal data types
- Creating and populating temporal tables
- Datetime functions
- Datetime formatting
- Type conversion
- Datetime arithmetic
- `TIMESTAMP` vs. `DATETIME`
- Flights dataset case study

---

## Week 18: Descriptive Statistics Continued

### 1. Session 39: Descriptive Statistics — Part 2

- Quantiles and Percentiles
- Five-Number Summary
- Boxplots
- Scatterplots
- Covariance
- Correlation
- Correlation vs. Causation
- Visualizing Multiple Variables

### 2. Session 40: Probability Distribution Functions — PDF, CDF and PMF

- Random Variables
- Probability Distributions
- Types of Probability Distribution Functions
- Probability Mass Function (PMF)
- Cumulative Distribution Function (CDF) of PMF
- Probability Density Function (PDF)
- Density Estimation
- Parametric and Non-parametric Density Estimation
- Kernel Density Estimation (KDE)
- Cumulative Distribution Function (CDF) of PDF

### 3. Session: SQL Datetime Case Study — Flights Dataset

- Datetime analysis using SQL
- Flights dataset case study

### 4. Session: Database Design, SQL Data Types and Normalization

- Different SQL data types:
  - Numeric
  - Text
  - Datetime
  - Miscellaneous
- Database Normalization
- Entity-Relationship (ER) Diagram

---

## Week 19: Probability Distributions

### 1. Session 41: Normal Distribution

- Uses of PDF in Data Science
- Two-dimensional density plots
- Normal Distribution:
  - Importance
  - Equation
  - Parameters
  - Intuition
- Standard Normal Variate
- Importance of the Z-table
- Empirical Rule
- Properties of Normal Distribution
- Skewness
- CDF of Normal Distribution
- Applications of Normal Distribution in Data Science

### 2. Session 42: Non-Gaussian Probability Distributions

- Kurtosis
- Excess Kurtosis
- Types of Kurtosis
- Q-Q Plot
- Uniform Distribution
- Log-normal Distribution
- Pareto Distribution

#### Data Transformations

- Mathematical Transformation
- Function Transformer
- Log Transformation
- Reciprocal Transformation
- Square and Square Root Transformations
- Power Transformer
- Box-Cox Transformation
- Yeo-Johnson Transformation

### 3. Session: Views and User-Defined Functions in SQL

- What are Views?
- Types of Views
- User-Defined Functions (UDFs)
- Syntax and Examples
- Benefits of User-Defined Functions

### 4. Session: Transactions and Stored Procedures

- Stored Procedures
- Benefits of Stored Procedures
- Database Transactions
- `COMMIT`
- `ROLLBACK`
- `SAVEPOINT`
- ACID Properties of Transactions

---

## Week 20: Inferential Statistics

### 1. Session 43: Central Limit Theorem

#### Probability Distributions

- Bernoulli Distribution
- Binomial Distribution
- PDF formula
- Graph of PDF
- Examples
- Criteria for Binomial Distribution
- Applications in Data Science

#### Sampling and CLT

- Sampling Distribution
- Intuition behind the Central Limit Theorem (CLT)
- CLT implementation using code
- Case study
- Assumptions of sampling

### 2. Session: Central Limit Theorem Proof

- Proof of the Central Limit Theorem

### 3. Session 44: Confidence Intervals

- Population vs. Sample
- Parameter vs. Estimate
- Point Estimate
- Confidence Interval
- Ways to Calculate Confidence Intervals
- Applications of Confidence Intervals
- Assumptions of the Z-procedure
- Formula and intuition of the Z-procedure
- Interpreting Confidence Intervals
- T-procedure and t-distribution
- Confidence Interval implementation using code

---

## Week 21: Hypothesis Testing

### 1. Session 45: Hypothesis Testing — Part 1

- Key idea of hypothesis testing
- Null and Alternative Hypotheses
- Steps in Hypothesis Testing
- Performing a Z-test
- Rejection Region and Significance Level
- Type I Error and Type II Error
- One-tailed vs. Two-tailed Tests
- Applications of Hypothesis Testing
- Hypothesis Testing in Machine Learning

### 2. Session 46: Hypothesis Testing — Part 2: P-value and T-tests

- What is a P-value?
- Interpreting P-values
- P-value in the context of a Z-test
- Introduction to T-tests
- Types of T-tests:
  - One-sample T-test
  - Independent two-sample T-test
  - Paired two-sample T-test
- Code examples of T-tests

### 3. Session: Chi-Square Test

- Chi-square distribution: Definition and Properties
- Chi-square test
- Goodness-of-fit test:
  - Steps
  - Assumptions
  - Examples
- Test for Independence:
  - Steps
  - Assumptions
  - Examples
- Applications in Machine Learning

### 4. Session: ANOVA

- Introduction to ANOVA
- F-distribution
- One-way ANOVA
- Steps of one-way ANOVA
- Geometric intuition
- Assumptions
- Python implementation
- Post-hoc tests
- Why a T-test is not used for comparing multiple groups
- Applications in Machine Learning

---

## Week 22: Linear Algebra

### 1. Session: Tensors — Linear Algebra Part 1(a)

- What are Tensors?
- Zero-dimensional (0D) Tensors
- One-dimensional (1D) Tensors
- Two-dimensional (2D) Tensors
- N-dimensional Tensors
- Rank, Axes and Shape
- Examples of 1D, 2D, 3D, 4D and 5D Tensors

### 2. Session: Vectors — Linear Algebra Part 1(b)

- What is Linear Algebra?
- What are Vectors?
- Vector examples in Machine Learning
- Row and Column Vectors
- Distance from Origin
- Euclidean Distance
- Scalar Addition and Subtraction (Shifting)
- Scalar Multiplication and Division (Scaling)
- Vector Addition and Subtraction
- Dot Product
- Angle Between Two Vectors
- Equation of a Hyperplane

### 3. Session: Matrices — Linear Algebra Part 2 (Computation)

- What are Matrices?
- Types of Matrices
- Matrix Equality
- Scalar Operations
- Matrix Addition and Subtraction
- Matrix Multiplication
- Transpose of a Matrix
- Determinant
- Minor
- Cofactor
- Adjoint
- Inverse of a Matrix
- Solving a System of Linear Equations

### 4. Session: Matrices — Linear Algebra Part 3 (Intuition)

- Basis Vectors
- Linear Transformations
- Linear Transformations in 3D
- Matrix Multiplication as Composition
- Testing the Commutative Law
- Determinant and Inverse
- Transformations for Non-square Matrices
- Why only square matrices can have inverses
- Why inverses are possible only for non-singular matrices

---

## Learning Objectives

- Understand descriptive and inferential statistics.
- Summarize datasets using statistical measures and visualizations.
- Analyze relationships using covariance and correlation.
- Understand probability distributions, PMF, PDF, CDF and KDE.
- Apply normal and non-Gaussian probability distributions.
- Understand sampling distributions and the Central Limit Theorem.
- Calculate and interpret confidence intervals.
- Perform hypothesis tests, Z-tests, T-tests, chi-square tests and ANOVA.
- Understand tensors, vectors, matrices and linear transformations.
- Apply fundamental mathematical concepts used in Machine Learning.
- Work with SQL datetime functions, database normalization and transactions.

## Technologies Covered

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SQL
- Statistics and Probability
- Linear Algebra
