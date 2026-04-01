# Машинное обучение: материалы курса ФКН НИУ ВШЭ

Публичный репозиторий с материалами для серии курсов по машинному обучению на ФКН НИУ ВШЭ.

Автор: [Андрей Боревский](https://www.hse.ru/org/persons/305061980/).

В репозитории собраны:

- лекции в формате PDF;
- семинарские ноутбуки;
- первые два домашних мини-проекта.

## Что Внутри

- [`lectures/`](lectures) - лекции;
- [`seminars/`](seminars) - семинарские ноутбуки;
- [`homeworks/`](homeworks) - домашние мини-проекты.

## Как Пользоваться

Лекции можно смотреть как обычные PDF. Семинары и домашние задания оформлены как Jupyter notebooks.

Для работы с ноутбуками достаточно `jupyter` / `jupyterlab` и базового стека `numpy`, `pandas`, `matplotlib`, `scikit-learn`. Для отдельных материалов может пригодиться `kaggle` CLI.

## План Тем

Ниже собран план тем и соответствие материалов внутри репозитория. Поле со ссылками на записи оставлено для последующего заполнения.

| № | Тема | Лекция | Семинар / практика | Записи |
| --- | --- | --- | --- | --- |
| 1 | Overview | [Overview и введение в ML](lectures/01-overview.pdf) | [Основы pandas](seminars/practice-00-pandas-basics.ipynb) | TODO |
| 2 | Linear Regression | [Линейная регрессия](lectures/02-linreg.pdf) | [Линейная регрессия в `sklearn`](seminars/practice-02-linear-regression-with-sklearn.ipynb), [Мини-проект B: линейные модели](homeworks/mini-project-b-linear-models.ipynb) | TODO |
| 3 | Gradient Descent | [Градиентный спуск](lectures/03-gradient-descent.pdf) | [Разминка по градиентному спуску](seminars/practice-01-gradient-descent-warmup.ipynb), [Практика по градиентному спуску](seminars/practice-01-gradient-descent-hands-on.ipynb), [Оптимизация и градиентные методы](seminars/practice-03-optimization-and-gradient-methods.ipynb) | TODO |
| 4 | Metrics | [Метрики](lectures/04-metrics.pdf) | [Признаки, препроцессинг и функции потерь](seminars/practice-02-feature-engineering-and-losses.ipynb), [Калибровка вероятностей](seminars/practice-06-probability-calibration.ipynb) | TODO |
| 5 | Logistic Regression I | [Логистическая регрессия, часть 1](lectures/05-logreg-part-1.pdf) | [Бинарная линейная классификация](seminars/practice-04-binary-linear-classification.ipynb), [Линейные классификаторы](seminars/practice-05-linear-classifiers.ipynb) | TODO |
| 6 | Logistic Regression II | [Логистическая регрессия, часть 2](lectures/06-logreg-part-2.pdf) | [Логистическая регрессия и SVM](seminars/practice-05-logreg-and-svm.ipynb), [Калибровка вероятностей](seminars/practice-06-probability-calibration.ipynb) | TODO |
| 7 | SVM | [Support Vector Machines](lectures/07-svm.pdf) | [Логистическая регрессия и SVM](seminars/practice-05-logreg-and-svm.ipynb) | TODO |
| 8 | Multiclass Classification | [Многоклассовая классификация](lectures/08-multiclass-classification.pdf) | [Логистическая регрессия и SVM](seminars/practice-05-logreg-and-svm.ipynb) | TODO |
| 9 | Decision Trees | [Решающие деревья](lectures/09-decision-trees.pdf) | [Практика по решающим деревьям](seminars/practice-07-decision-trees.ipynb) | TODO |
| 10 | BVD | [Bias-Variance Decomposition](lectures/10-bias-variance-decomposition.pdf) | [Случайный лес и BVD](seminars/practice-09-random-forest.ipynb) | TODO |
| 11 | Bagging + RF | [Bagging и Random Forest](lectures/11-bagging-and-random-forest.pdf) | [Случайный лес и BVD](seminars/practice-09-random-forest.ipynb) | TODO |
| 12 | GB | [Gradient Boosting](lectures/12-gradient-boosting.pdf) | [Бустинг: базовая практика](seminars/practice-10-boosting-basics.ipynb), [Продвинутые техники бустинга](seminars/practice-11-advanced-boosting.ipynb) | TODO |

## Домашние Мини-Проекты

- [Мини-проект A: tabular data](homeworks/mini-project-a-tabular-data.ipynb) - работа с `pandas`, табличными данными и визуализацией;
- [Мини-проект B: linear models](homeworks/mini-project-b-linear-models.ipynb) - признаки, линейные модели и регрессия.

## Дополнительные Материалы

### Базовые внешние ресурсы

- [Yandex Handbook по машинному обучению](https://education.yandex.ru/handbook/ml)
- [Yandex Handbook по Python](https://education.yandex.ru/handbook/python)
- [Курс Евгения Соколова по машинному обучению на ФКН](https://github.com/esokolov/ml-course-hse)

### Русский

- [Что такое машинное обучение](https://education.yandex.ru/handbook/ml/article/mashinnoye-obucheniye)
- [Линейные модели](https://education.yandex.ru/handbook/ml/article/linear-models)
- [Метрики классификации и регрессии](https://education.yandex.ru/handbook/ml/article/metriki-klassifikacii-i-regressii)
- [Кросс-валидация](https://education.yandex.ru/handbook/ml/article/kross-validaciya)
- [Оптимизация в машинном обучении](https://education.yandex.ru/handbook/ml/article/optimizaciya-v-ml)
- [Модули `math` и `numpy`](https://education.yandex.ru/handbook/python/article/moduli-math-i-numpy)
- [Модуль `pandas`](https://education.yandex.ru/handbook/python/article/modul-pandas)
- [Регуляризация: краткий конспект](https://deepmachinelearning.ru/docs/Machine-learning/Base-concepts/Regularization)
- [Линейный классификатор: обзор от ODS / Habr](https://habr.com/ru/companies/ods/articles/323890/#lineynyy-klassifikator)

### English

- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Mathematics for Machine Learning](https://mml-book.github.io/)
- [An Introduction to Statistical Learning](https://www.statlearning.com/)
- [Probabilistic Machine Learning](https://probml.github.io/pml-book/)
- [CS229: Machine Learning](https://cs229.stanford.edu/)
- [scikit-learn User Guide](https://sklearn.org/stable/user_guide.html)
- [pandas: Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)
- [NumPy User Guide](https://numpy.org/doc/stable/user/index.html)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Plotly for Python: Getting Started](https://plotly.com/python/getting-started/)

## Где Читался Курс

Материалы из этого репозитория использовались и адаптировались для курсов по машинному обучению на нескольких программах ФКН НИУ ВШЭ:

- [Машинное обучение в магистратуре «Искусственный интеллект в маркетинге и управлении продуктом»](https://www.hse.ru/ma/ai-productmanagement/courses/929560265.html)
- [Машинное обучение в магистратуре «Финансовые технологии»](https://www.hse.ru/ma/alfafintech/)

Сами программы можно посмотреть здесь:

- [Искусственный интеллект в маркетинге и управлении продуктом](https://www.hse.ru/ma/ai-productmanagement/)
- [Финансовые технологии](https://www.hse.ru/ma/alfafintech/)

## Благодарности

При подготовке части материалов использовались открытые образовательные ресурсы и конспекты ФКН, включая материалы курса [Евгения Соколова](https://github.com/esokolov/ml-course-hse).

Отдельная благодарность авторам [Yandex Handbook по машинному обучению](https://education.yandex.ru/handbook/ml) и [Yandex Handbook по Python](https://education.yandex.ru/handbook/python) за качественные и доступные учебные материалы.
