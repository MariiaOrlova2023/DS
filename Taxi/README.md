## Данные
Исторические данные о заказах такси в аэропортах.
## Задача
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания.
## Технологии
Pandas,Python,Scikit-learn, LightGBM, CatBoost, временные ряды
## Вывод
Провели декомпозицию временного ряда, чтобы посмотреть сезонность и тренд. Для анализа ресемплировали данные по одному дню в отдельный датасет. Лучшие результаты показала модель градиентного бустинга CatBoostRegressor
