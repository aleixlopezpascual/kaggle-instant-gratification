# instant-gratification
Kaggle competition 2019-03

https://www.kaggle.com/c/instant-gratification

## Overview

In this competition you had to solve a binary classification problem evaluated with AUC. 
The key factor of this contest was to infer that the data was synthetic, and that you could 
reverse-engineer how the data set was generated. The data set appeared to be 512 data sets 
concatenated where each sub dataset was believed to be created by Sklearn's make_classification. 
EDA suggested that the data resided in 33 + x (where 0 <= x <= 14) dimensional space within 6 hyper-ellipsoids. 
Each hyper-ellipsoid corresponded to a multivariate Gaussian distribution. Based on this information, 
I decided to apply Quadratic Discriminant Anlysis, Pseudo Labeling and Gaussian Mixture Models.
