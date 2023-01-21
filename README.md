# Support-Vector-Machine-Galaxy-Classification
This is the code for investigating Galaxy Classification using support vector machines. I created models using rbf, linear, and ploynomial kernels and C levels 1.0, 10.0, 50.0, 100.0, and 1000.0.

***Conclusions***
Our best model comes from the support vector machine model with a rbf kernel and C = 50.0. The accuacy when predicted on the testing set is 86%.
Our ROC AUC from the model is .85 which is close to 1 so we can conclude that our classifier does a good job classifing galaxies.

***Data***
The dataset can be downloaded from [kaggle](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17). The dataset includes 100,000 stellar observations of galaxies, stars and quasars taken by the SDSS (Sloan Digital Sky Survey).


***Libraries:***
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
