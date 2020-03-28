# ML_UsdRatePrediction
Skillbox Python DataScience Intensive

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
