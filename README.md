# Naive-Bayes-and-SVM-Implementation
Group research project predicting the survival rate in the titanic dataset through naive bayes and support vector machines

# Specification
This is an overview of the techniques used for this project. The Bernoulli Naive Bayes algorithm was used since it is designed for binary data.
C-Support Vector Classification was also used for the SVM implementation. Each implementation used an 80/20 split for the training and testing data.
The data was also shuffled prior to training. Accuracy was calculated for 100 runs, and then the final performance metrics were calculated at the end.

# Results
The SVM implementation was shown to perform better in terms of accuracy, but there was a trade-off with computational performance.
The Naive Bayes implementation generally had an accuracy of 70% and higher, whereas the SVM implementation reached accuracies of 80%.
With further optimization, results could be improved. The use of additional models could also serve to find the best fit for this particular dataset.
