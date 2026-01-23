# [Hands-on machine learning with Scikit-Learn, Keras and TensorFlow: concepts, tools, and techniques to build intelligent systems](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
Géron, Aurélien

## Chapter 1: The Machine Learning Landscape
- TODO pages 1-26
- The first application of ML, spam filters, is used as an example for why ML should be used. Instead of maintaining a complicated list of spam filters, you can let ML learn the patterns for you
- ML is great for (p. 7):
    - Problems requiring complicated or long lists of rules
    - Fluctuating environments (re-training is easier than changing all your code rules)
    - Getting new insights about complex problems and large amounts of data
- Pages 8/9 outline a ton of different use cases for ML
- Types of ML Systems
    - Unsupervised, semi-supervised, self-supervised, and others
    - Incremental vs on the fly learning (online vs batch learning)
    - Do they compare new data points to known ones? Or detect patterns in training data and build a predictive model?
- Training Supervision
    - Supervised learning includes labels
    - Unsupervised learning uses unlabeled data (dimensionality reduction, clustering, anomaly detection)
    - Semi-supervised uses partially labeled data (Think when you upload photos of your family to a photo app. At the start they are unlabeled, so clustering is used, then once a label is assigned to one it knows all the others are the same)
    - Self-supervised. Generating labeled dataset from unlabeled one. An image based example is provided on page 15
- 