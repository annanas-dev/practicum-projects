# 🚗 Определение стоимости автомобилей

## 📝 Описание проекта

Сервис по продаже автомобилей с пробегом **«Не бит, не крашен»** разрабатывает приложение, позволяющее пользователю быстро узнать **рыночную стоимость своего автомобиля**.

В распоряжении — исторические данные: технические характеристики, комплектации и цены автомобилей.  
Цель — построить модель для определения стоимости.

📌 Заказчику важны:
- 🎯 Качество предсказания  
- ⚡ Скорость предсказания  
- ⏱️ Время обучения  

## 🛠️ Навыки и инструменты

- **python**
- **pandas**, **numpy**, **scipy**, **time**, **warnings**, **itertools**
- **matplotlib**, **seaborn**
- **phik**
  - `phik_matrix`, `plot_correlation_matrix`
- `sklearn.model_selection`: **train_test_split**, **RandomizedSearchCV**
- `sklearn.impute`: **SimpleImputer**
- `sklearn.preprocessing`: **OneHotEncoder**, **StandardScaler**, **MinMaxScaler**, **RobustScaler**, **OrdinalEncoder**
- `sklearn.pipeline`: **Pipeline**
- `sklearn.compose`: **ColumnTransformer**
- `sklearn.metrics`: **root_mean_squared_error**
- `sklearn.linear_model`: **LinearRegression**
- `sklearn.tree`: **DecisionTreeRegressor**
- `sklearn.ensemble`: **AdaBoostRegressor**
- `lightgbm`: **LGBMRegressor**
- `catboost`: **CatBoostRegressor**
