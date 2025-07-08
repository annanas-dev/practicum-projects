# 😠 Классификация токсичных комментариев для интернет-магазина «Викишоп» с использованием BERT

## 📝 Описание проекта

Интернет-магазин **«Викишоп»** запустил сервис, позволяющий пользователям редактировать и дополнять описания товаров, как в вики-сообществах. Клиенты предлагают правки и комментируют изменения других пользователей.

Для поддержания дружелюбной атмосферы магазину нужен инструмент, который автоматически выявляет токсичные комментарии и отправляет их на модерацию.

🎯 Цель — обучить модель классифицировать комментарии на позитивные и негативные с метрикой качества **F1 не меньше 0.75**.

## 🛠️ Навыки и инструменты

- **python**
- **pandas**, **numpy**, **seaborn**, **matplotlib**
- **nltk** (лемматизация, стоп-слова)
- **re** (регулярные выражения)
- **torch**, **transformers** (BERT)
- **requests**
- **warnings**
- **vaderSentiment**: **SentimentIntensityAnalyzer**
- **wordcloud**
- **tqdm** (прогресс-бары)
- `sklearn.model_selection`: **train_test_split**, **RandomizedSearchCV**
- `sklearn.pipeline`: **Pipeline**
- `sklearn.metrics`: **f1_score**
- `sklearn.linear_model`: **LogisticRegression**
- `sklearn.neighbors`: **KNeighborsClassifier**
- `sklearn.tree`: **DecisionTreeClassifier**
- `sklearn.svm`: **SVC**
- **lightgbm**: **LGBMClassifier**
