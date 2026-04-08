# Машинное обучение: материалы курса ФКН НИУ ВШЭ

Публичный репозиторий с материалами для серии курсов по машинному обучению на ФКН НИУ ВШЭ.

Лектор: [Андрей Боревский](https://www.hse.ru/org/persons/305061980/)

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
| 1 | Overview | [Overview и введение в ML](lectures/01-overview.pdf) | [Основы pandas](seminars/practice-00-pandas-basics.ipynb) | [Первая запись](https://youtu.be/KEZnL-ek6BI?si=gedqj8MYH6EqV5iV) |
| 2 | Linear Regression | [Линейная регрессия](lectures/02-linreg.pdf) | [Линейная регрессия в `sklearn`](seminars/practice-02-linear-regression-with-sklearn.ipynb), [Мини-проект B: линейные модели](homeworks/mini-project-b-linear-models.ipynb) | [Вторая запись](https://youtu.be/CfsVtg6DexU?si=RdfcxgQlGCp7kdAW) |
| 3 | Gradient Descent | [Градиентный спуск](lectures/03-gradient-descent.pdf) | [Разминка по градиентному спуску](seminars/practice-01-gradient-descent-warmup.ipynb), [Практика по градиентному спуску](seminars/practice-01-gradient-descent-hands-on.ipynb), [Оптимизация и градиентные методы](seminars/practice-03-optimization-and-gradient-methods.ipynb) | [Третья запись](https://youtu.be/dXVE_Oau60w?si=pN1P1Wp4BC_vWx_P) |
| 4 | Metrics | [Метрики](lectures/04-metrics.pdf) | [Признаки, препроцессинг и функции потерь](seminars/practice-02-feature-engineering-and-losses.ipynb) | [Четвертая запись](https://youtu.be/-pTFcxbt07o?si=51lHhvCDjV-G9t8I) [Пятая запись](https://youtu.be/6suyW61-apY?si=jtI02M3hvejAWJXQ) |
| 5 | Logistic Regression I | [Логистическая регрессия, часть 1](lectures/05-logreg-part-1.pdf) | [Бинарная линейная классификация](seminars/practice-04-binary-linear-classification.ipynb) | [Шестая запись](https://youtu.be/rYEp3tZwHKA?si=ktbBQqKVCnO6dth5)  |
| 6 | Logistic Regression II | [Логистическая регрессия, часть 2](lectures/06-logreg-part-2.pdf) | [Линейные классификаторы](seminars/practice-05-linear-classifiers.ipynb)| [Седьмая запись](https://youtu.be/qX3mcE-1iJ8?si=OH7hqKj3YiIdyXgu) |
| 7 | SVM | [Support Vector Machines](lectures/07-svm.pdf) | [Логистическая регрессия и SVM](seminars/practice-05-logreg-and-svm.ipynb) | [Седьмая запись](https://youtu.be/qX3mcE-1iJ8?si=OH7hqKj3YiIdyXgu) |
| 8 | Multiclass Classification | [Многоклассовая классификация](lectures/08-multiclass-classification.pdf) | [Калибровка вероятностей](seminars/practice-06-probability-calibration.ipynb) | TODO |
| 9 | Decision Trees | [Решающие деревья](lectures/09-decision-trees.pdf) | [Практика по решающим деревьям](seminars/practice-07-decision-trees.ipynb) | [Восьмая запись](https://youtu.be/q6Ubpioa1Yk?si=aYefUGz8OUFMZ8yv) |
| 10 | BVD | [Bias-Variance Decomposition](lectures/10-bias-variance-decomposition.pdf) | [Случайный лес и BVD](seminars/practice-09-random-forest.ipynb) | TODO |
| 11 | Bagging + RF | [Bagging и Random Forest](lectures/11-bagging-and-random-forest.pdf) | [Случайный лес и BVD](seminars/practice-09-random-forest.ipynb) | TODO |
| 12 | GB | [Gradient Boosting](lectures/12-gradient-boosting.pdf) | [Бустинг: базовая практика](seminars/practice-10-boosting-basics.ipynb), [Продвинутые техники бустинга](seminars/practice-11-advanced-boosting.ipynb) | TODO |

## Домашние Мини-Проекты

- [Мини-проект A: tabular data](homeworks/mini-project-a-tabular-data.ipynb) - работа с `pandas`, табличными данными и визуализацией;
- [Мини-проект B: linear models](homeworks/mini-project-b-linear-models.ipynb) - признаки, линейные модели и регрессия.

## Дополнительные Материалы

Ниже — подборка внешних материалов, которые хорошо дополняют лекции и семинары из репозитория. Список разбит на несколько уровней: быстрый вход, системные курсы и книги, практическая документация, а также материалы по отдельным темам курса.

### Базовые внешние ресурсы

- [Yandex Handbook по машинному обучению](https://education.yandex.ru/handbook/ml)
- [Yandex Handbook по Python](https://education.yandex.ru/handbook/python)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Курс Евгения Соколова по машинному обучению на ФКН](https://github.com/esokolov/ml-course-hse)
- [Stanford CS229: Machine Learning](https://cs229.stanford.edu/)
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)

### Системные курсы и книги

- [Mathematics for Machine Learning](https://mml-book.github.io/)
- [An Introduction to Statistical Learning](https://www.statlearning.com/)
- [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
- [Pattern Recognition and Machine Learning — Christopher Bishop](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- [Probabilistic Machine Learning](https://probml.github.io/pml-book/)
- [CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)

### Практика и документация по Python-стеку

- [NumPy User Guide](https://numpy.org/doc/stable/user/index.html)
- [pandas: Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Plotly for Python: Getting Started](https://plotly.com/python/getting-started/)

### Материалы по темам курса

#### 1. Overview / введение в ML

- [Что такое машинное обучение — Yandex Handbook](https://education.yandex.ru/handbook/ml/article/mashinnoye-obucheniye)
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)
- [CS229: course page](https://cs229.stanford.edu/)
- [An Introduction to Statistical Learning](https://www.statlearning.com/)

#### 2. Linear Regression

- [Линейные модели — Yandex Handbook](https://education.yandex.ru/handbook/ml/article/linear-models)
- [CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)
- [scikit-learn: Linear Models](https://scikit-learn.org/stable/modules/linear_model.html)
- [ISLR](https://www.statlearning.com/)

#### 3. Gradient Descent / Optimization

- [Оптимизация в машинном обучении — Yandex Handbook](https://education.yandex.ru/handbook/ml/article/optimizaciya-v-ml)
- [CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)
- [Mathematics for Machine Learning](https://mml-book.github.io/)
- [PRML — Bishop](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

#### 4. Metrics / Model Evaluation

- [Метрики классификации и регрессии — Yandex Handbook](https://education.yandex.ru/handbook/ml/article/metriki-klassifikacii-i-regressii)
- [Кросс-валидация — Yandex Handbook](https://education.yandex.ru/handbook/ml/article/kross-validaciya)
- [scikit-learn: Model Evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html)
- [scikit-learn: Cross-Validation](https://scikit-learn.org/stable/modules/cross_validation.html)

#### 5–6. Logistic Regression / Linear Classification / Calibration

- [Линейные модели — Yandex Handbook](https://education.yandex.ru/handbook/ml/article/linear-models)
- [Линейный классификатор: обзор от ODS / Habr](https://habr.com/ru/companies/ods/articles/323890/#lineynyy-klassifikator)
- [scikit-learn: Linear Models](https://scikit-learn.org/stable/modules/linear_model.html)
- [scikit-learn: Probability Calibration](https://scikit-learn.org/stable/modules/calibration.html)
- [CalibratedClassifierCV](https://scikit-learn.org/stable/modules/generated/sklearn.calibration.CalibratedClassifierCV.html)

#### 7. SVM

- [CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)
- [scikit-learn: Support Vector Machines](https://scikit-learn.org/stable/modules/svm.html)
- [PRML — Bishop](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

#### 8. Multiclass Classification

- [scikit-learn: Multiclass and Multioutput Algorithms](https://scikit-learn.org/stable/modules/multiclass.html)
- [scikit-learn: Linear Models](https://scikit-learn.org/stable/modules/linear_model.html)
- [CS229 Lecture Notes](https://cs229.stanford.edu/main_notes.pdf)

#### 9. Decision Trees

- [scikit-learn: Decision Trees](https://scikit-learn.org/stable/modules/tree.html)
- [CS229 Notes: Decision Trees + Ensemble Methods](https://cs229.stanford.edu/notes_archive/rf-notes.pdf)
- [ISLR](https://www.statlearning.com/)
- [ESL](https://hastie.su.domains/ElemStatLearn/)

#### 10. Bias–Variance Decomposition

- [ISLR](https://www.statlearning.com/)
- [ESL](https://hastie.su.domains/ElemStatLearn/)
- [PRML — Bishop](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

#### 11. Bagging / Random Forest

- [scikit-learn: Ensemble Methods](https://scikit-learn.org/stable/modules/ensemble.html)
- [scikit-learn: Random Forests and other randomized tree ensembles](https://scikit-learn.org/stable/modules/ensemble.html#forest)
- [CS229 Notes: Decision Trees + Ensemble Methods](https://cs229.stanford.edu/notes_archive/rf-notes.pdf)
- [ISLR](https://www.statlearning.com/)

#### 12. Gradient Boosting

- [scikit-learn: Gradient Boosting](https://scikit-learn.org/stable/modules/ensemble.html#gradient-boosting)
- [scikit-learn: Histogram-Based Gradient Boosting](https://scikit-learn.org/stable/modules/ensemble.html#histogram-based-gradient-boosting)
- [CS229 Notes: Decision Trees + Ensemble Methods](https://cs229.stanford.edu/notes_archive/rf-notes.pdf)
- [ESL](https://hastie.su.domains/ElemStatLearn/)

### Отдельно для подготовки по математике

- [Mathematics for Machine Learning](https://mml-book.github.io/)
- [Модули `math` и `numpy` — Yandex Handbook по Python](https://education.yandex.ru/handbook/python/article/moduli-math-i-numpy)
- [NumPy User Guide](https://numpy.org/doc/stable/user/index.html)

### Отдельно для практики с данными и визуализацией

- [Модуль `pandas` — Yandex Handbook по Python](https://education.yandex.ru/handbook/python/article/modul-pandas)
- [pandas: Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Plotly for Python: Getting Started](https://plotly.com/python/getting-started/)

### Как использовать эту подборку

- Если тема изучается впервые: начать с Yandex Handbook / Google ML Crash Course.
- Если нужен более академический и связный текст: читать ISLR, CS229, PRML, ESL.
- Если нужно сразу применять методы в коде: смотреть `scikit-learn User Guide` и официальную документацию `pandas` / `numpy` / `matplotlib`.
- Если нужно повторить математику под линейные модели, оптимизацию и вероятности: использовать Mathematics for Machine Learning.
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
