# 5001_self_project


  The project is about predicting the running time of SGDClassifier models in python scikit-learn package. 

  SGDClassifier implements regularized linear models for classification with stochastic gradient descent (SGD) learning. According to the theory of *SGDClassifier*, if the input data set is a matrix of size $(n,p)$, training has a cost of
$O(n\overline{p}k)$ , where $k$ is the number of iterations (epochs) and $\overline{p}$ is the average number of non-zero attributes per sample.

  The synthetic dataset for training is generated using *sklearn.datasets.make_classification*. According to its explaination，‘n_samples’ means the number of samples, ‘n_features’ means the total number of features.
  
## About

  The ipynb file records my work in details; xgboost.csv records my result. train.csv and test.csv are identical with files provided in Kaggle.
  
  *(There might be small differences because I changed parameters in my code to test the results and forgot to save a copy.)*
  
  
  **Programming language:** python
  
  **Packages:** pandas, numpy, sklearn, xgboost, matplotlib
  
  **Attention:** before run the code in jupyter notebook, change 'path' to your own work path
