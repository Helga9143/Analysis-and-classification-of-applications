# Analysis-and-classification-of-applications
Данный проект предназначен для классификации текстов с использованием алгоритмов машинного обучения, таких как Наивный Байес.

## 1. Клонируйте репозиторий
Сначала клонируйте этот репозиторий на свой локальный компьютер:
## 2. Установите необходимые библиотеки:
  pandas
   scikit-learn
   joblib
   matplotlib
   seaborn
## Запуск обучения модели
1. Убедитесь, что файл `applications.csv` находится в исходной директории проекта. Этот файл должен содержать данные для обучения модели.
2. Запустите скрипт для обучения (или воспользуйтесь созданой(?))
3. После выполнения скрипта будет создана модель и сохранены файлы `model.pkl` и `vectorizer.pkl`.

## Использование предсказаний (Inference)

1. Убедитесь, что модель и векторизатор уже сохранены (вы должны были выполнить шаги по обучению модели).

2. Запустите скрипт для выполнения предсказаний:
   python predict.py

3. Вы можете редактировать скрипт `predict.py`, чтобы тестировать различные входные заявки. Внутри скрипта вы можете изменить строку приложения, например:
     print(predict("условия получения премии"))
   
