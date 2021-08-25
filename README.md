# ML_UsdRatePrediction
Skillbox Python DataScience Intensive

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=Python&logoColor=fffffb) ![Pandas](https://img.shields.io/badge/-Pandas-05122A?style=flat&logo=Pandas) ![MathPlotLib](https://img.shields.io/badge/-MathPlotLib-05122A?style=flat&logo=MathPlotLib) ![Scikit-learn](https://img.shields.io/badge/-Scikit_learn-05122A?style=flat&logo=sklearn)

Учебный интенсив Skillbox DataScience "Предсказание курса доллара" с помощью Python.
Предсказание производится на основе исторических данных.
Использованы библиотеки:
- Pandas - для получения данных из файла Excel,
- MathPlotLib для построения графиков.
- Scikit-learn (SKLearn) для алгоритмов/

Для оценки использовалась средняя абсолютная ошибка (mean_absolute_error from sklearn.metrics).

Алгоритмы:
- LinearRegression,
- KNeighborsRegressor,
- MLPRegressor,
- RandomForestRegressor,

Автоматизация подбора параметров и кросс-валидация:
- GridSearchCV from sklearn.model_selection
