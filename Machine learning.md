# Introduction to Machine Learning

## Brief Introduction
- The first widely recognized ML application was the spam filter.
- Machine Learning involves programming computers to learn from data.
- It is used to solve complex problems and often outperforms traditional approaches.
- Data mining applies ML to large datasets to discover patterns.

## Applications:
- Brain tumor detection using Convolutional Neural Networks (CNN).
- Chatbot creation using Natural Language Processing (NLP).
- Fraud detection in credit card transactions using Anomaly detection.

## Types of Machine Learning
- **Supervised Learning**
- **Semisupervised Learning**
- **Unsupervised Learning**
- **Reinforcement Learning**
- **Online Learning**
- **Batch Learning**
- **Instance-based Learning**
- **Model-based Learning**

## Supervised Learning
- Training data contains labels.
- Important algorithms include:
  1. k-Nearest Neighbors
  2. Linear Regression
       ```python
    from sklearn.linear_model import LinearRegression
    model = LinearRegression()
   model.fit(X_train, y_train)
  ```
  4. Logistic Regression
  5. Support Vector Machines (SVMs)
  6. Decision Trees and Random Forests
  ```python
  from sklearn.tree import DecisionTreeClassifier
  model = DecisionTreeClassifier()
  model.fit(X_train, y_train)
  ```
  7. Neural Networks

## Unsupervised Learning
- Training data is unlabeled.
- Important algorithms include:
  1. Clustering
     - K-Means
       ```python
  from sklearn.cluster import KMeans
  model = KMeans(n_clusters=3)
  model.fit(X)
  ```
     - DBSCAN
     - Hierarchical Cluster Analysis (HCA)
  2. Anomaly detection and novelty detection
     - One-class SVM
     - Isolation Forest
  3. Visualization and dimensionality reduction
     - Principal Component Analysis (PCA)
     - Kernel PCA
     - Locally Linear Embedding (LLE)
     - t-Distributed Stochastic Neighbor Embedding (t-SNE)
  4. Association rule learning
     - Apriori
     - Eclat

## Semisupervised Learning
- Uses partially labeled data.
- Combinations of unsupervised and supervised algorithms.

## Reinforcement Learning
- An agent observes the environment, selects actions, receives rewards or penalties, updates policy, and repeats until optimal policy is achieved.

## Batch Learning
- Trained with all available data and runs without learning incrementally.
- Also known as offline learning.
- Requires retraining the system from scratch to incorporate new data.

## Online Learning
- Trained incrementally with new data, individually or in small batches.
- Fast, cheap, and requires fewer computing resources.
- Requires monitoring and adaptation to changing data.

## Instance-based Learning
- Learns examples by heart and generalizes to new cases using similarity measures.

## Model-based Learning
- Builds a model of examples and makes predictions based on that model.
- Involves defining parameter values, performance measures, and making predictions.
