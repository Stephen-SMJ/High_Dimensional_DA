# High-dimensional analysis on transactions for potential customers

This project is done by R language.

The original dimension is  4459 × 4735.

By PCA, The PC1 is 0.02392, and PC589 is 0.7001. This means I can describe 70% of the data using only 589 variables. So, I reduced the dimension to 4459 × 589, which extremely reduced the dimension.

Result:

| Model/Score | RMSE     | MAE       |
| ----------- | -------- | --------- |
| Linear      | 2.928906 | 1.824384  |
| Lasso       | 1.926282 | 1.501868  |
| Ridge       | 1.67311  | 1.362062  |
| Elastic     | 1.680414 | 1.369406  |
| SVM         | 1.697674 | 1.380873  |
| RF          | 1.514563 | 1.357896  |
| MLP         | 1.954889 | 1.55686   |
| XGB         | 1.679852 | 1.359144  |
| LightGBM    | 1.170869 | 0.9386955 |

