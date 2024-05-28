# misis-ml-final-project

|    | models        | r2        |
|---:|:--------------|:----------|
|  0 | CB            | 0.1266    |
|  1 | CB (PI)       | 0.133     |
|  2 | CB (PI & SVD) | **0.134** |
|  3 | LineReg       | -0.007    |
|  4 | LineReg (PI)  | -0.007    |
|  5 | RF            | 0.11      |
|  6 | RF (PI)       | 0.106     |
|  7 | ETR           | 0.0978    |
|  8 | ETR (PI)      | 0.0926    |

`CB` - CatBoostRegressor with all features and text processing

`CB (PI)` - CatBoostRegressor with feature selection and text processing

`CB (PI & SVD)` - CatBoostRegressor with feature selection, text processing and svd compression of the remaining features

`LineReg` - LinearRegression with all features

`LineReg (PI)` - LinearRegression with feature selection

`RF` - RandomForestRegressor with all features

`RF (PI)` - RandomForestRegressor with feature selection

`ETR` - ExtraTreesRegressor with all features

`ETR (PI)` - ExtraTreesRegressor with feature selection
