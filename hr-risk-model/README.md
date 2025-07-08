# 👥 HR-аналитика: удовлетворённость и отток сотрудников

## 📝 Описание проекта

HR-аналитики компании **«Работа с заботой»** помогают бизнесу **оптимизировать управление персоналом**.  
Компания предоставляет данные, а аналитики предлагают решения, как избежать:

- 💸 финансовых потерь  
- 🚪 оттока сотрудников  

🔍 Цель проекта — автоматизировать процесс анализа с помощью **машинного обучения**.

### Задачи:

1. 📊 Построить модель, предсказывающую **уровень удовлетворённости** сотрудника работой (по данным анкеты).
2. 🚨 Построить модель, предсказывающую **вероятность увольнения** сотрудника из компании.

Почему это важно бизнесу:
- Уровень удовлетворённости напрямую влияет на риск увольнения.  
- Внезапные увольнения, особенно ключевых сотрудников, могут нести значительные потери.

## 🛠️ Навыки и инструменты

- **python**
- **pandas**, **numpy**, **seaborn**, **matplotlib**, **scipy**
- `sklearn.metrics`: **make_scorer**, **roc_auc_score**
- `sklearn.model_selection`: **train_test_split**, **RandomizedSearchCV**
- `sklearn.pipeline`: **Pipeline**
- `sklearn.compose`: **ColumnTransformer**
- `sklearn.impute`: **SimpleImputer**
- `sklearn.preprocessing`: **LabelEncoder**, **OneHotEncoder**, **OrdinalEncoder**, **StandardScaler**, **MinMaxScaler**, **RobustScaler**
- `sklearn.linear_model`: **LinearRegression**, **LogisticRegression**
- `sklearn.tree`: **DecisionTreeRegressor**, **DecisionTreeClassifier**
- `sklearn.svm`: **SVR**, **SVC**
- `sklearn.neighbors`: **KNeighborsClassifier**
- `sklearn.dummy`: **DummyRegressor**
- **phik**
  - `phik_matrix`, `plot_correlation_matrix`
- **shap**
