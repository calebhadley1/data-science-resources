# Table of Contents

0. Helpful Links
    - [Dataset Locations](3_dataset_locations.md)
1. Introduction to Data Analytic Thinking
    - [Data Science for Business - Chapter 1](2_data_science_for_business.md)
    - [Case Studies](1_data_science_case_studies.md)
    - Key concepts:
        - Non-obvious applications of DS
        - Data as a strategic asset
2. Business Problems and Data Science Solutions
    - [Data Science for Business - Chapter 2](2_data_science_for_business.md)
    - [Supervised vs Unsupervised Learning](https://www.kaggle.com/discussions/general/229219)
    - Key concepts
        - Types of models
        - CRISP-DM
        - Business vs Data understanding
        - Data preparation
        - Modeling
        - Evaluation
        - Deployment
        - Engineering vs DS management
        Statistics
        - Summary statistics vs the field of stats
        - Database Querying
        - Data Warehousing
        - Regression Analysis
        - Machine Learning and Data Mining
3. Introduction to Predictive Modeling: From Correlation to Supervised Segmentation Pt 1
4. Introduction to Predictive Modeling: From Correlation to Supervised Segmentation Pt 2
    - [Data Science for Business - Chapter 3](2_data_science_for_business.md)
    - [Information Gain and Entropy](https://victorzhou.com/blog/information-gain/)
    - [Decision Trees](https://medium.com/@fe.valvekens/understanding-decision-trees-38294f5c8f25)
    - Key concepts:
        - Decision and classification trees
        - Decision line
        - Instance space
        - Laplace Correction
        - Branching
        - Leaf
        - Feature selection
        - Information gain
        - Tree induction
        - Model accuracy vs intelligibility
        - Build supervised segmentation model by recursively finding informative attrs to split the instance space on
            - Results in a tree model & the numeric params of the model (prob estimates of leaf nodes)
5. Fitting a Model to Data Pt 1
    - [Data Science for Business - Chapter 4](2_data_science_for_business.md)
    - [Support Vector Machines](https://www.kdnuggets.com/2016/07/support-vector-machines-simple-explanation.html)
    - Key concepts:
        - Linear discriminants
        - Support Vector Machines (Soft vs Kernal)
        - Model parameter optimization
        - Objective function
        - Loss function
        - Linear regression
        - Logistic regression
6. Fitting a Model to Data Pt 2
    - [Data Science for Business - Chapter 4](2_data_science_for_business.md)
    - [12 Important Performance Metrics that every data scientist must know](https://medium.com/@pingsubhak/12-important-performance-metrics-that-every-data-scientist-must-know-110f59b2e305)
7. Overfitting and its Avoidance Pt 1
    - [Data Science for Business - Chapter 5](2_data_science_for_business.md)
    - [What is overfitting? (AWS)](https://aws.amazon.com/what-is/overfitting)
    - Key concepts:
        - Overfitting
        - Holdout Data
        - Cross Validation
        - Fitting Graphs
        - Learning Curves
        - How Logistic Regression can overfit (and how SVM can help)
        - How overfitting is related to spurious correlations
        - Nearest neighbors & K Nearest neighbors
        - Regularization
8. Overfitting and its Avoidance Pt 2
    - [A Gentle Intro to Neural Nets](https://medium.com/data-science/a-gentle-introduction-to-neural-networks-series-part-1-2b90b87795bc)
    - [ML for Begineers - An Intro to Neural Nets](https://victorzhou.com/blog/intro-to-neural-networks/)
    - Personal resource reccomendations for Neural nets:
        - [Part 1: Main Ideas of Neural Networks](https://www.youtube.com/watch?v=CqOfi41LfDw)
        - [Part 2: Backpropagation](https://www.youtube.com/watch?v=IN2XmBhILt4)
        - [Part 3: ReLU](https://www.youtube.com/watch?v=68BZ5f7P94E)
        - [Part 4: Multiple Inputs and Outputs](https://www.youtube.com/watch?v=83LYR-1IcjA)
        - [Part 5: ArgMax and SoftMax](https://www.youtube.com/watch?v=KpKog-L9veg)
        - [Part 6: Cross Entropy](https://www.youtube.com/watch?v=6ArSys5qHAU)
        - [Part 7: Cross Entropy Derivatives and Backpropagation](https://www.youtube.com/watch?v=xBEh66V9gZo)
        - [Part 8: Image Classification with Convolutional Neural Networks (CNNs)](https://www.youtube.com/watch?v=HGwBXDKFk9I)
    - Key concepts:
        - Cross-validation
        - Learning curves
        - Nested holdout testing
9. Similarity, Neighbors, and Clusters Part 1
    - [K-Nearest Neighbour Algorithm](https://www.kaggle.com/code/just4jcgeorge/k-nearest-neighbour-algorithm)
10. Similarity, Neighbors, and Clusters Part 2
    - [Data Science for Business - Chapter 6: Similarity, Neighbors, and Clusters](2_data_science_for_business.md)
    - [Intelligibility is a key component to trust in machine learning](https://rbcborealis.com/research-blogs/intelligibility-key-component-trust-machine-learning/)
11. Decision Analytic Thinking I: What is a Good Model?
    - [Data Science for Business - Chapter 7: Decision Analytics Thinking I: What Makes a Good Model?](2_data_science_for_business.md)
    - [Failure of Classification Accuracy for Imbalanced Class Distributions](https://machinelearningmastery.com/failure-of-accuracy-for-imbalanced-class-distributions/)
    - Key concepts:
        - Accuracy
        - Confusion matrix
        - Accuracy and unbalanced classes
        - Compare accuracy and cost/benefit
        - Expected value
        - Identify some other metrics—these are important!
        - Explain what is meant by “doing better than a baseline”
        - Describe the characteristics of a dataset that can be useful for addressing a real-world problem
12. Visualizing Model Performance
    - [Data Science for Business - Chapter 8: Visualizing Model Performance](2_data_science_for_business.md)
    - [AUC-ROC Curve in Machine Learning Clearly Explained](https://www.kaggle.com/discussions/general/343302)
    - Key concepts:
        - Ranking vs classifying
        - Profit curves
        - ROC curves (Receiver Operating Characteristic) 
        - Lift curves
13. Evidence and Probabilities
    - [Data Science for Business - Chapter 9: Evidence and Probabilities](2_data_science_for_business.md)
    - [Bayes' Theorem](https://www.cuemath.com/data/bayes-theorem/)
    - Key concepts:
        - Bayes’ Rule
        - Naïve Bayes
        - Evidence lift
14. Representing and Mining Text
    - Representations
        - A way of storing data so that we can access it using data science
    - Bag of Words
        - A numeric representation for text data
    - Term frequency-inverse document frequency (TF-IDF)
        - Evaluates the importance of a word by looking at frequency
    - N-grams
        - Counts frequency of sequences of words
    - Named entity extraction
        - Allows us to correlate different words with same meaning (NY vs New York)
    - [Data Science for Business - Chapter 10: Representing and Mining Text](2_data_science_for_business.md)
    - [How TF-IDF Works](https://towardsdatascience.com/how-tf-idf-works-3dbf35e568f0/)
    - Key concepts:
        - Explain representation
        - Explain bag of words
        - Explain term frequency-inverse document frequency (TF-IDF)
        - Explain n-grams
        - Describe named entity extraction