Dataset shape: (9471, 17)

Shape after removing extra columns: (9471, 15)

Missing values:
CO(GT)          1797
PT08.S1(CO)      480
PT08.S2(NMHC)    480
PT08.S3(NOx)     480
T                480
RH               480

Rows available for modelling: 7674

Training samples: 6139
Testing samples : 1535

Missing values handled using median imputation.

Linear Regression model trained successfully.

Test Set Evaluation
--------------------
MAE  : 0.3709
RMSE : 0.6154
R^2  : 0.8182
