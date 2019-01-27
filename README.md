# Prediction of credit clients repayment abilities with machine learning

### Overview

The notebooks were developed when attending to the Kaggle challange [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/).

Goal was to attend the challage and to write a paper about how we proceeded. Following you will find the abstract to the paper which is located [here.](paper/ws_proj_homecredit.pdf)

Abstract — We describe and analyze the approach used to attend the 'Home Credit Default Risk' challenge on Kaggle.
The goal of the challenge is to predict the ability for a client to repay a loan. 
The provided data contains personal and wealth information together with information about previous loans, 
credit card balances and ratings from other agencies. We will show different methods for handling missing values and 
selection of features. For training the classifiers we used two different approaches. In the first approach we used LightGBM 
and XGBoost with hyper-parameter optimization. For the second approach we used stacking, a ensemble technique that combines
the predictions of multiple learning algorithms. At the end we compared both approaches and the obtained results are presented.

### Howto

1. Make sure the original data (application_train.csv and application_test.csv) are located under [data/original](data/original). 
Goto [Kaggle Home Credit Default Risk Data](https://www.kaggle.com/c/home-credit-default-risk/data) and download the two files 
to the given directory.

2. [Install](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) and [start](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) jupyter notebook in the source directory.

3. Execute the the notebooks sequentially (order by filename), by this new files will be created under [data/pickles/](data/pickles).
