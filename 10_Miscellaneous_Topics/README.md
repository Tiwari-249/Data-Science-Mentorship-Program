# Miscellaneous Topics

This section covers NoSQL databases, model explainability, API development, cloud-based machine learning, imbalanced data handling, and regular expressions.

## 1. NoSQL

- **Introduction:** Overview of NoSQL databases
- **Types:**
  - Document
  - Key-Value
  - Column-Family
  - Graph
- **Use Cases:** When to use NoSQL over SQL databases
- **Popular Databases:** MongoDB, Cassandra, Redis, Neo4j

## 2. Model Explainability

- **Introduction:** Importance of interpretable models
- **Techniques:** LIME, SHAP, Feature Importance
- **Application:** Applying techniques to various models
- **Best Practices:** Ensuring reliable and accurate explanations

## 3. FastAPI

- **Introduction:** Modern, fast web framework for building APIs
- **Features:** Type checking, automatic validation, documentation
- **Building APIs:** Steps and best practices
- **Deployment:** Hosting and scaling FastAPI applications

## 4. AWS SageMaker

- **Introduction:** Fully managed service for machine learning
- **Features:** Model building, training, deployment
- **Usage:** Workflow from data preprocessing to model deployment
- **Best Practices:** Optimizing costs and performance

## 5. Handling Imbalanced Data

### Session 1: Introduction to Imbalanced Data

1. What Is Imbalanced Data?
2. Problems with Imbalanced Data
3. A Quick Detour!
4. Why Do Algorithms Perform Badly on Imbalanced Data?
5. Why Is Imbalanced Data a Huge Deal?
6. **Techniques**
   - Under Sampling
   - Over Sampling
   - SMOTE
   - Hybrid Sampling
   - Class Weighting
   - Cost-Sensitive Learning
   - Ensemble Methods
   - Threshold Tuning

### Session 2: Oversampling Techniques

1. Recap
2. Random Oversampling
3. SMOTE
4. Borderline SMOTE
5. ADASYN

### Session 2: Oversampling Techniques Continued

1. SVM SMOTE
2. SMOTENC
3. When to Use Which Technique

### Session 3: Undersampling Techniques

1. Recap
2. Random Undersampling Technique
3. **Tomek Links**
   - What Is a Tomek Link?
   - How Does It Work?
   - Code
4. Edited Nearest Neighbors
5. Neighborhood Cleaning Rule
6. Cluster Centroids

## 6. Regular Expressions (RegEx)

### Session 1: Introduction to Regular Expressions

1. **Introduction**
   - What Are Regular Expressions?
   - Why Use Regular Expressions?
2. What Is a Raw String?
3. The `re` Module
4. **Searching Functions**
   - `match()`
   - `search()`
   - `findall()`
   - `finditer()`
5. **Metacharacters**
   - Dot (`.`)
   - Caret (`^`)
   - Dollar (`$`)
6. **Character Sets**
   - Custom Character Sets
   - Character Ranges
   - Character Negation
   - Predefined Character Sets
7. **Quantifiers**
   - Greedy
   - Non-Greedy or Lazy

### Session 2: Advanced Regular Expressions

1. **Grouping**
   - Captured Groups
   - Named-Captured Groups
   - Back References
   - Non-Capture Groups
   - Alternation
2. **Modifications**
   - Split
   - Substitution
3. **Assertions**
   - Look Ahead
   - Look Behind
4. Flags

---

## Learning Objectives

- Understand NoSQL databases and their use cases.
- Learn model explainability techniques such as LIME, SHAP, and Feature Importance.
- Build and deploy APIs using FastAPI.
- Explore machine learning workflows with AWS SageMaker.
- Handle imbalanced datasets using oversampling and undersampling techniques.
- Use regular expressions for searching, pattern matching, grouping, and substitution.
