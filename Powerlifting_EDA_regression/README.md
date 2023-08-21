# Жим штанги лёжа - предсказание рекорда. Описание проекта.

Сылка на Kaggle: https://www.kaggle.com/datasets/kukuroo3/powerlifting-benchpress-weight-predict

В данном датасете представлена информация о спортсменах - пауэрлифтерах: их данные и рекорды в трёх основных упражнениях (присед, становая тяга, жим лёжа). Рекорд в жиме лёжа в данном проекте является целевым признаком, для предсказания его на основе остальных признаков будет решаться задача регрессии. В качестве метрики будем использовать MAPE.

Итоги проекта: лучше всего показала модель CatBoost, её величина метрики MAPE на тестовой выборке равна 11.58 %.