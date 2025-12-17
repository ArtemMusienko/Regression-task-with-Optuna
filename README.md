
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

## Regression task with Optuna
[Датасет](https://storage.yandexcloud.net/academy.ai/japan_cars_dataset.csv) состоит из информации по японским автомобилям. В качестве метрики во время обучения модели используется **mean_absolute_error** (**MAE**).

Важный этап в реализации модели - создание новых признаков на основе существующих. Этот шаг способствует большей сходимости категориальных признаков с целевым.

Использование такого инструмента, как **Optuna**, немало важный шаг к достижению идеальной модели. **Optuna** подбирает необходимые нам параметры, архитектуру модели и даже регуляризацию. Это происходит в результате её внутреннего обучения и сохранения лучших показателей, которые в дальнейшем будут интегрированы уже в нашу основную модель.

*Результат работы кода:*

> *Средняя абсолютная процентная ошибка (MAPE) на валидационной выборке: 0.42%  
> Средняя абсолютная ошибка (MAE) на валидационной выборке: 4.18*

**Примечание**. Подробную информацию о датасете можно узнать на  [kaggle.com](https://www.kaggle.com/datasets/doaaalsenani/used-cars-dataets/data).

> Настоятельно рекомендую использовать **графический ускоритель T4** в
> **Google Colab** для запуска этого кода!
