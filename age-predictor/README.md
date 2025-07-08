# 🧑‍🦳 Определение возраста по фотографии

## 📝 Описание проекта

Сетевой супермаркет **«Хлеб-Соль»** внедряет систему компьютерного зрения для обработки фотографий покупателей.  
Фотофиксация в прикассовой зоне поможет:

- 📊 Анализировать покупки и рекомендовать товары по возрастной группе.  
- 🛡️ Контролировать работу кассиров при продаже алкоголя.

**Задача:** построить модель, которая по фотографии определяет **приблизительный возраст человека**.  
📉 Целевая метрика — **MAE < 7**.

## 🛠️ Навыки и инструменты

- **python**
- **pandas**, **matplotlib**, **seaborn**, **plotly.express**
- `sklearn.metrics`: **accuracy_score**
- `tensorflow.keras.layers`: **Dense**, **Conv2D**, **GlobalAveragePooling2D**
- `tensorflow.keras.models`: **Sequential**
- `tensorflow.keras.optimizers`: **Adam**
- `tensorflow.keras.preprocessing.image`: **ImageDataGenerator**
- `tensorflow.keras.applications.resnet`: **ResNet50**
