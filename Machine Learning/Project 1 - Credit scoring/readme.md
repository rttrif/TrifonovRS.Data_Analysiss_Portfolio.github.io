## Credit scoring

### Project Objectives

Требуется, на основании имеющихся данных о клиентах банка, построить модель, используя обучающий датасет, для прогнозирования невыполнения долговых обязательств по текущему кредиту. Выполнить прогноз для примеров из тестового датасета

### Success criteria

#### Целевая переменная

Credit Default - факт невыполнения кредитных обязательств

#### Метрика качества

F1-score (sklearn.metrics.f1_score)

#### Требования к решению

Целевая метрика
- F1 > 0.5
- Метрика оценивается по качеству прогноза для главного класса (1 - просрочка по кредиту)

#### Task type

- Задача кредитного скоринга относится к классу задач классфикикации.

### Result

- В качестве итоговой модели из 11 расматриваемых в проекте выбрана модель CatBoost
- Итоговое значение метрики на контрольной выборке 0.5415
