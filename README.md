## Diabetes Prediction <br>
Hello Kagglers, <br>
In this notebook I tried to create an optimal model for Diabetes Prediction from given .csv data. <br>
Points covered are:<br>
0] Exploratory Data Analysis and Visualization <br>
1] Data Normalized Distribution <br>
2] Data Up-Sampling for Imbalance data <br>
3] Feature Engineering and Selection <br>
4] Fine tuning of Models. <br>
<br>
If you found this notebook helpful, your Upvote Will Encourage Me !!! 😀😇😊<br>
<br>

## Results 💹📈<br>

Benchmark : 75.97  Without any processing <br>
XGBoost : 87.50  After Distribution Normalization + Up-Sampling + Feature Selection <br>
XGBoost & Random Forest : 89.00  After Distribution Normalization + Up-Sampling + Feature Selection + Fine Tuning + Random State in Data Spliting <br>
Gradient Boosting Classifier : 92.20  After removing outliers <br>

<br>
# Problem Statement : Diabetes Prediction <br>
<br>
## Some EDA <br>
# Given data visualized in a single window <br>
![alt text](https://github.com/OMIII1997/Diabetes--EDA-Acc_89-F1-Score_89-Precision_89.5-/blob/master/screen_shots/pairplot.png)
<br>
# XGB_feature_importance-1 <br>
![alt text](https://github.com/OMIII1997/Diabetes--EDA-Acc_89-F1-Score_89-Precision_89.5-/blob/master/screen_shots/xgb_feature_imp1.png)
<br>
# XGB_feature_importance-2 <br>
![alt text](https://github.com/OMIII1997/Diabetes--EDA-Acc_89-F1-Score_89-Precision_89.5-/blob/master/screen_shots/xgb_feature_imp2.png)
<br>
# Data is normally distributed using boxcox <br>
![alt text](https://github.com/OMIII1997/Diabetes--EDA-Acc_89-F1-Score_89-Precision_89.5-/blob/master/screen_shots/normal_distributed_pairplor.png)
<br>
# Random Forest 89% Acc, Confusion Matrix <br>
![alt text](https://github.com/OMIII1997/Diabetes--EDA-Acc_89-F1-Score_89-Precision_89.5-/blob/master/screen_shots/RF_confusion_matrix.png)
<br>
