# Bankruptcy-Prediction
## Mining the Polish Bankruptcy Data
##### Tags: Data Mining, Machine Learning, Data Visualization.

#### Co-created by [Sree Keerthi Matta](https://github.com/sreekmatta)

#### Links:   
Project presentation: [slideshow](https://1drv.ms/p/s!Ar1FVxllTqB6yWZl9iXqvFmmqU7H)   
Dataset: [Polish Bankruptcy Dataset](http://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data)   

### Summary:

Bankruptcy prediction is the task of predicting bankruptcy and various measures of financial distress of firms, and is important due to the relevance for creditors and investors in evaluating the likelihood that a firm may go bankrupt. 

The aim of predicting financial distress is to develop a predictive model that combines various econometric parameters which allow foreseeing the financial condition of a firm. In this project we document our observations as we explore, build, and compare, some of the widely used classification models:   

<b>
  
  1. Gaussian Naïve Bayes  
  2. Logistic Regression   
  3. Decision Trees   
  4. Random Forests   
  5. Extreme Gradient Boosting   
  6. Balanced Bagging 
</b> 

We have chosen the Polish companies’ bankruptcy data set where synthetic features were used to reflect higher-order statistics.  

We begin by carrying out data preprocessing and exploratory analysis where we impute the missing data values using some of the popular data imputation techniques like **Mean, k-Nearest Neighbors, Expectation-Maximization and Multivariate Imputation by Chained Equations (MICE)**.    

To address the data imbalance issue, we apply **Synthetic Minority Oversampling Technique (SMOTE)** to oversample the minority class labels. 

Later, we model the data using K-Fold Cross Validation on the said models, and the imputed and resampled datasets. 

Finally, we analyze and evaluate the performance of the models on the validation datasets using several metrics such as accuracy, precision, recall, etc., and rank the models accordingly. 
