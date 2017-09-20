Using the PIMA Indian data, I would like to predict which individuals will be more likely to have diabetes by looking at features like age, BMI etc.

My client would be Native Americans who are closely related to Pima Indians who are living in central and southern Arizona.

The data is available at https://www.kaggle.com/uciml/pima-indians-diabetes-database and will be in csv format.

My initial thought about the data is that this data is pretty clean and has ~8 features.  I will use common feature selection method to take the most important features out and do cross validation on 5 major machine learning models (Logistic Regression, Gaussian NB, K-nearest neighborhood, Decision tree and Support vector machine).

The codes are included in pima_indians_diabetes.ipynb
