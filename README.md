Review classification using ML (NLP) 

Implementation of Natural Language Processing and Text Mining course with the following specifications:

 1. You may notice that the classifier is built around a feature set constituted of 1,40,000 vocabulary words, recording the frequency of words in the document. Repeat the procedure using document-frequency times inverse document based feature. Compare the classification results.

 2. You may notice that the program uses LogisticRegression and Naives’ Bayes classifiers. Try to repeat the testing using other classifiers that you may call upon from skit-learn package. Use the majority voting rule to aggregate the result of the various classifiers (e.g., counting the number of classifiers that yield sentiment as 1 and 0, and then select the class assigned by the largest number of classifiers).

 3. I would like to use another feature set extracted from TF.IDF in 2). First use the principal component analysis PCA available in sklearn-decomposition, and construct a feature vector of 10 highest PCA vector set from the feature set 2).  Repeat the training of classifiers  and the testing.

 4. Repeat 5) using latent discriminant analysis dimension reduction (also available in sklearn python package. Use a 10 component dimension vector for the feature set, and repeat the training and classification of the classifiers.

 5. Construct a new feature set constituted of a concatenation of PCA and LDA feature vectors. Repeat the training and testing of the classifiers.  Conclude about the performance of the classification with respect to various feature sets.

 6. Suggest a new feature representation of your own that you may think is more relevant to the nature of review you have, and test its performances with the classifiers.
