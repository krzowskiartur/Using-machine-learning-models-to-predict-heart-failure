# Engineering work
##
This study compares the effectiveness of machine learning models, specifically Random Forests, with a Multilayer Perceptron (MLP) in predicting mortality among patients affected by heart failure. The research was conducted using a database of 299 patients, characterized by class imbalance (32% deaths and 68% survivors). The main challenges were the small dataset size, class imbalance, and the elimination of data leakage caused by one of the features (time).
##
To improve model quality, hyperparameter optimization and data preparation were applied. For the MLP, regularization and class balancing techniques (undersampling, SMOTE) were implemented. Ultimately, a better result was achieved by Random Forest (F1-score: 0.680, Recall: 0.895) compared to MLP (F1-score: 0.638). The work demonstrates that on small datasets, classical algorithms can outperform neural networks. It is important to emphasize that appropriate data preparation is highly significant, especially for MLP.
##
Key words: heart failure, mortality prediction, machine learning, Random Forest, Multilayer Perceptron (MLP), imbalanced dataset, small dataset size, data leakag.
