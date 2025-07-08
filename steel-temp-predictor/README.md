# 🔥 Модель предсказания температуры стали для металлургического комбината «Стальная птица»

## 📝 Описание проекта

Чтобы оптимизировать производственные расходы, металлургический комбинат **«Стальная птица»** решил снизить потребление электроэнергии на этапе обработки стали. Для этого необходимо контролировать температуру сплава и предсказывать её с помощью модели.

Сталь обрабатывают в металлическом ковше вместимостью около 100 тонн, облицованном огнеупорным кирпичом. Расплавленную сталь нагревают графитовыми электродами, корректируют химический состав добавлением легирующих материалов, проводят циклы измерений и обработки, чтобы достичь оптимальной температуры и состава. Полученный расплав направляют на дальнейшую обработку и производство заготовок-слябов.

🎯 Цель — построить модель, предсказывающую температуру сплава на основе технологических параметров, чтобы использовать её для имитации технологического процесса и оптимизации энергозатрат.

## 🛠️ Навыки и инструменты

- **python**
- **pandas**, **numpy**, **matplotlib**, **seaborn**
- **warnings**
- `scipy.stats`
- `sklearn.metrics`: **mean_absolute_error**
- `sklearn.model_selection`: **train_test_split**, **RandomizedSearchCV**
- `sklearn.pipeline`: **Pipeline**
- `sklearn.compose`: **ColumnTransformer**
- `sklearn.impute`: **SimpleImputer**
- `sklearn.preprocessing`: **StandardScaler**, **MinMaxScaler**, **RobustScaler**
- `sklearn.linear_model`: **LinearRegression**
- `sklearn.tree`: **DecisionTreeRegressor**
- `sklearn.svm`: **SVR**
- **lightgbm**: **LGBMRegressor**
- **catboost**: **CatBoostRegressor**
- `sklearn.dummy`: **DummyRegressor**
- **phik**: **phik_matrix**
- `phik.report`: **plot_correlation_matrix**
