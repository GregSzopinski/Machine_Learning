# introductory-machine-learning
Some minor ML projects. This repo served as sort-of portfolio, documenting my first attempts at machine learning.

## KaggleDays Warsaw 2018
I had an amazing opportunity to participate in this great event and compete against some of kaggle masters. Finally, our team reached 12 place (of around 40 teams) - our score was decent, but still far away from perfection - some major improvements could be made. My aim is to implement these improvments and check how good our score will be. 
Sidenote: Unfortunately, test and train datasets are too big for github, but can be accessed [here](https://www.kaggle.com/c/kaggledays) 

## Predict if someone will earn over 50k $ anually
Adut AKA Census Income dataset. Classification on public data. I generated some new features and used tree-based methods (CART, Random Forest, XGBoost). Even with simpler methods results seem promising. This kind of information can help target some products, offers, ideas etc. in a better way. You'll find here some examples of hyperparameter optmization ("manual" or bayesian with hyperopt)

## Allstate
NN and XGBoost regression on dataset from Kaggle Allstate Claims Severity competition. Quite promising results (at least from practical/business point of view, Kaggle is another story...), but still some space for improvements. This was part of my course work during first tier/edition of [DataWorkshop](http://www.dataworkshop.eu/)

## Drug Consumption
Another classification, this time on drug-related data from UCI ML Repository. Many classification problems are associated with this data - I decided to predict if someone is cannabis user. This is my small contribution to 'de-demonization' of this drug. Simple, but fun.

## SVD from scratch
Singular Value Decomposition is one of popular dimensionality reduction technques (also one of many useful ML tool with roots in linear algebra). There are many good implementations in popular python packages, but I tried to do it on my own, step by step. I wasn't trying to reinvent the wheel - the aim was to gain more thorough understanding of this technique and to improve my math skills.
