# 🚕 Прогнозирование заказов такси для компании «Чётенькое такси»

## 📝 Описание проекта

Компания **«Чётенькое такси»** собрала исторические данные о заказах такси в аэропортах. Для привлечения большего числа водителей в периоды пиковой нагрузки необходимо спрогнозировать количество заказов на следующий час.

Основная задача — построить модель прогнозирования числа заказов такси, используя исторические данные. Значение метрики RMSE на тестовой выборке должно быть не больше 48.

Данные хранятся в файле `taxi.csv`. Целевая переменная — столбец **num_orders** (число заказов).

🎯 Цель — построить точную модель прогноза с учётом временных и сезонных особенностей заказов.

## 🛠️ Навыки и инструменты

- **python**
- **pandas**, **numpy**, **matplotlib**
- **calendar**
- `statsmodels.tsa.seasonal`: **seasonal_decompose**
- `math`: **ceil**
- `sklearn.model_selection`: **train_test_split**, **RandomizedSearchCV**, **TimeSeriesSplit**
- `sklearn.impute`: **SimpleImputer**
- `sklearn.preprocessing`: **OneHotEncoder**, **StandardScaler**, **MinMaxScaler**, **RobustScaler**, **OrdinalEncoder**
- `sklearn.pipeline`: **Pipeline**
- `sklearn.compose`: **ColumnTransformer**
- `sklearn.linear_model`: **LinearRegression**
- **lightgbm**: **LGBMRegressor**
- `sklearn.svm`: **SVR**
- `sklearn.metrics`: **root_mean_squared_error**
