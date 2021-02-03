# Проект - прогнозирование оттока
В этом репозитории находится финальный проект специализации "Машинное обучение и анализ данных".
Ниже приведена общая информация о каждом этапе проекта и используемые инструменты в процессе выполнения проекта.

[id1]: https://github.com/Lisstrange/churn_project/blob/main/EDA.ipynb "EDA"
[id2]: https://github.com/Lisstrange/churn_project/blob/main/Basic%20Decision.ipynb "Basic Decision"
[id3]: https://github.com/Lisstrange/churn_project/blob/main/model_expirements.ipynb "Expirements with model"
[id4]: https://github.com/Lisstrange/churn_project/blob/main/economic_effect_model.ipynb "Economic model"
[id5]: https://github.com/Lisstrange/churn_project/blob/main/Final.ipynb "Conclusions on the project "




| № | Название ноутбука | Описание | Инструменты |
| :- | :--------------------- | :---------------------------| :---------------------------|
| [1][id1]  | [Разведочный анализ данных][id1] | Анализ данных и их визуализация. Поиск зависимостей.  | Pandas, Seaborn, matplotlib. |
| [2][id2]  | [Пострение BaseLine решения][id2] | Провожу эксперимент в выборе лучшей модели без подбора гиперпараметров, эксперементируя с помощью различных методов обработки исходного датасета | Pandas, Sklearn, Xgboost , Catboost, Lightgbm, Category_encoders. |
| [3][id3]  | [Эксперименты с моделью, финальное решение][id3] | Иследование поведения модели в различных условиях: изменения объема выборки, изменения весов модели, числа признаков и т.д. Оценка качества модели. | Pandas, NumPy, Sklearn, Xgboost, Catboost, Seaborn, Matplotlib, Category_encoders, Optuna. |
| [4][id4]  | [Оценка экономического эффекта][id4] | В качестве оценки эффективности проделанной работы, была реализована экономическая модель работы компании, с моделью и без. Построил граффики прибыли.| Pandas, Sklearn, Xgboost, Seaborn , Matplotlib |
| [5][id5]  | [Итоги проделанной работы][id5] | Рассказал цель данного проекта, описал этапы реализации конечного алгоритма, показал результаты проделанной работы. Рассказал о важных моментах и киллер фичах, которые я узнал во время работы. | Текст и картинки
