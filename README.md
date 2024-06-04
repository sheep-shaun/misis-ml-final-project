# misis-ml-final-project

|    | models        | r2        |
|---:|:--------------|:----------|
|  0 | CB            | 0.1266    |
|  1 | CB (PI)       | 0.133     |
|  2 | CB (PI & SVD) | **0.134** |
|  3 | CB wo tf      | 0.123     |
|  4 | LineReg       | -0.007    |
|  5 | LineReg (PI)  | -0.003    |
|  6 | RF            | 0.11      |
|  7 | RF (PI)       | 0.1       |
|  8 | ETR           | 0.0978    |
|  9 | ETR (PI)      | 0.103     |
|  10| MLP with PI   | -0.0065   |
|  11| conv1d with PI| 0.0443    |

`CB` - CatBoostRegressor with all features and text processing

`CB (PI)` - CatBoostRegressor with feature selection and text processing

`CB (PI & SVD)` - CatBoostRegressor with feature selection, text processing and svd compression of the remaining features

`CB wo tf` - CatBoostRegressor without text features

`LineReg` - LinearRegression with all features

`LineReg (PI)` - LinearRegression with feature selection

`RF` - RandomForestRegressor with all features

`RF (PI)` - RandomForestRegressor with feature selection

`ETR` - ExtraTreesRegressor with all features

`ETR (PI)` - ExtraTreesRegressor with feature selection

`MLP with PI` - Multi-layer Perceptron with feature selection

`conv1d with PI` - model with conv1d and linear layers
