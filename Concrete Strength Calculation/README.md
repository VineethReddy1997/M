
## PROJECT

**Concrete Strength Calculation**

**GOAL**
>Implementtion of different algorithms like random forest, logistic regression, and XGBoost to see which gives better accuracy.

**DATASET**

> https://www.kaggle.com/prathamtripathi/regression-with-neural-networking

**DESCRIPTION**

>The main aim of the project is to calculate the strength of the concrete using Machine Learning techniques.

**WORK DONE**

* Analyzed the data and found insights such as correlation, missing values etc.
* Made a filtered csv with less noise data. (Refer : `eda-concrete-strength.ipynb`)
* Next trained model with algorithms with default parameters:
	* Linear Regression
	* RBF SVM
	* Decision Tree
	* Random Forest
	* XGBoost
* In this XGBoost performed the best with 5.29 rmse. (Refer : `baseline-models-concrete-strength-regression.ipynb`)
* Also added an approach on getting optimal parameters on XGBoost with GPU.(Refer : `xgboost-tuning-concrete-strength-gpu.ipynb`)

**MODELS USED**

1. Linear Regression : Linear regression is easier to implement, interpret, and very efficient to train.

2. RBF SVM : SVM performs well on classification problems when size of dataset is not too large. Support Vector Machine can also be used as a regression method, maintaining all the main features that characterize the algorithm (maximal margin).

3. Decision Tree : Decision trees help you to evaluate your options. Decision Trees are excellent tools for helping you to choose between several courses of action. They provide a highly effective structure within which you can lay out options and investigate the possible outcomes of choosing those options.

4. Random Forest : It **provides higher accuracy through cross validation**. Random forest regressor will handle the missing values and maintain the accuracy of a large proportion of data. If there are more trees, it won't allow over-fitting trees in the model.

5. XGBoost : XGBoost is **a library for developing fast and high performance gradient boosting tree models**. XGBoost achieves the best performance on a range of difficult machine learning tasks.

**LIBRARIES NEEDED**

* Numpy
* Pandas
* Matplotlib
* scikit-learn
* xgboost
* seaborn
  
**Images** 
>Pending
**CONCLUSION**

* We investigated the data, checking for data unbalancing, visualizing the features, and understanding the relationship between different features. We then investigated two predictive models. The data was split into three parts, a train set, a validation set, and a test set. For the first five  base models, we only used the train and test set.

* We started with Linear Regression, SVM, Decision Tree, Random Forest and XGBoost for which we obtained RMSE of 8.453319,8.749276,7.020702,5.659124 and 5.294385 respectively, when predicting the target for the test set.

* We followed with XGB regressor and optimizing it using Grid search CV and achieved rmse of (4.551) and r2 score of (0.9194) for the prediction of the test set target values.  

**CONTRIBUTION**

>- Created by [Vineeth Reddy](https://linktr.ee/vineethreddy1997)

## Follow me on..
>[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vineethreddy1997/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VineethReddy1997)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vineethreddywithds@gmail.com)
[![website](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://vineethdata.github.io/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/vineeth_reddy_2426/)
[![Linktree](https://img.shields.io/badge/linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/vineethreddy1997)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/gangulavineeth1)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/vineethreddygangula)
[![Stack overflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/18168904/vineeth-reddy-gangula)
