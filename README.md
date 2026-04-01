# Машинное обучение: материалы курса ФКН НИУ ВШЭ

Публичный репозиторий с материалами для серии курсов по машинному обучению на ФКН НИУ ВШЭ.

Автор: [Андрей Боревский](https://www.hse.ru/org/persons/305061980/).

В репозиторий вошла только публичная и полезная часть материалов:

- лекции в формате PDF;
- семинарские ноутбуки;
- первые два практических домашних задания.

Черновики, `.key`-презентации, служебные артефакты, дубли и тяжёлые промежуточные файлы в публичную версию не включены.

## Что Внутри

- [`lectures/`](lectures) - лекционные PDF-файлы;
- [`seminars/`](seminars) - ноутбуки семинаров и небольшие локальные данные, которые действительно нужны для запуска;
- [`homeworks/`](homeworks) - первые два практических домашних задания.

## Как Пользоваться

Лекции можно смотреть как обычные PDF. Семинары и домашние задания оформлены как Jupyter notebooks.

Часть ноутбуков скачивает данные автоматически по ходу выполнения. Для отдельных материалов могут понадобиться:

- `jupyter` / `jupyterlab`;
- базовый стек `numpy`, `pandas`, `matplotlib`, `scikit-learn`;
- `kaggle` CLI для отдельных семинаров, где данные берутся из Kaggle.

## План Тем

Ниже собран рабочий план тем и соответствие материалов внутри репозитория. Поле со ссылками на записи оставлено для последующего заполнения.

| № | Тема | Лекция | Семинар / практика | Записи |
| --- | --- | --- | --- | --- |
| 1 | Введение в машинное обучение | [Введение в ML](lectures/01-course-overview-and-ml-intro.pdf) | [Основы pandas](seminars/practice-00-pandas-basics.ipynb) | TODO |
| 2 | Линейная регрессия | [Линейная регрессия](lectures/02-linear-regression.pdf) | [Линейная регрессия в `sklearn`](seminars/practice-02-linear-regression-with-sklearn.ipynb), [ДЗ 2: линейная регрессия](homeworks/hw-02-linear-regression.ipynb) | TODO |
| 3 | Градиентный спуск и оптимизация | [Градиентный спуск и оптимизация](lectures/03-gradient-descent-and-optimization.pdf) | [Разминка по градиентному спуску](seminars/practice-01-gradient-descent-warmup.ipynb), [Практика по градиентному спуску](seminars/practice-01-gradient-descent-hands-on.ipynb), [Оптимизация и градиентные методы](seminars/practice-03-optimization-and-gradient-methods.ipynb) | TODO |
| 4 | Линейная классификация | [Линейная классификация](lectures/04-linear-classification.pdf) | [Бинарная линейная классификация](seminars/practice-04-binary-linear-classification.ipynb), [Линейные классификаторы](seminars/practice-05-linear-classifiers.ipynb) | TODO |
| 5 | Метрики, регуляризация и валидация | [Метрики, регуляризация и валидация](lectures/05-metrics-regularization-and-validation.pdf) | [Логистическая регрессия и SVM](seminars/practice-05-logreg-and-svm.ipynb), [Калибровка вероятностей](seminars/practice-06-probability-calibration.ipynb) | TODO |
| 6 | Метод опорных векторов | [Метод опорных векторов](lectures/06-support-vector-machines.pdf) | [Логистическая регрессия и SVM](seminars/practice-05-logreg-and-svm.ipynb) | TODO |
| 7 | Решающие деревья | [Решающие деревья](lectures/07-decision-trees.pdf) | [Практика по решающим деревьям](seminars/practice-07-decision-trees.ipynb) | TODO |
| 8 | Ансамбли и случайный лес | [Ансамбли и случайный лес](lectures/08-ensembles-and-random-forest.pdf) | [Случайный лес](seminars/practice-09-random-forest.ipynb) | TODO |
| 9 | Градиентный бустинг | [Градиентный бустинг](lectures/09-gradient-boosting.pdf) | [Бустинг: базовая практика](seminars/practice-10-boosting-basics.ipynb) | TODO |
| 10 | Продвинутый бустинг и практические трюки | [Продвинутый бустинг](lectures/10-advanced-boosting.pdf) | [Продвинутые техники бустинга](seminars/practice-11-advanced-boosting.ipynb) | TODO |
| 11 | Работа с текстами и прикладные пайплайны | [Тексты и прикладной ML](lectures/11-texts-and-applied-ml.pdf) | [Классификация текстов](seminars/practice-08-text-classification.ipynb) | TODO |
| 12 | Ненаблюдаемое обучение и кластеризация | [Кластеризация](lectures/12-clustering.pdf) | материал семинара будет добавлен отдельно | TODO |

## Домашние Задания

- [ДЗ 1: `pandas` и визуализация](homeworks/hw-01-pandas-and-visualization.ipynb) - работа с `pandas`, табличными данными и базовой визуализацией;
- [ДЗ 2: линейная регрессия](homeworks/hw-02-linear-regression.ipynb) - признаки, линейные модели и регрессия.

## Дополнительные Материалы

### 1. Вход в ML и общая картина

- [Machine Learning Handbook: что такое машинное обучение](https://education.yandex.ru/handbook/ml/article/mashinnoye-obucheniye)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
- [An Introduction to Statistical Learning](https://www.statlearning.com/)

### 2. Python, NumPy, pandas и визуализация

- [Модули `math` и `numpy` в Python Handbook от Яндекса](https://education.yandex.ru/handbook/python/article/moduli-math-i-numpy)
- [Модуль `pandas` в Python Handbook от Яндекса](https://education.yandex.ru/handbook/python/article/modul-pandas)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [pandas: Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)
- [NumPy User Guide](https://numpy.org/doc/stable/user/index.html)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)

### 3. Линейные модели, метрики и валидация

- [Линейные модели](https://education.yandex.ru/handbook/ml/article/linear-models)
- [Метрики классификации и регрессии](https://education.yandex.ru/handbook/ml/article/metriki-klassifikacii-i-regressii)
- [Кросс-валидация](https://education.yandex.ru/handbook/ml/article/kross-validaciya)
- [Регуляризация: краткий конспект](https://deepmachinelearning.ru/docs/Machine-learning/Base-concepts/Regularization)
- [Регуляризация в линейных моделях](https://education.yandex.ru/handbook/ml/article/linear-models#regulyarizaciya)
- [Линейный классификатор: обзор от ODS / Habr](https://habr.com/ru/companies/ods/articles/323890/#lineynyy-klassifikator)

### 4. Оптимизация и градиентные методы

- [Оптимизация в машинном обучении](https://education.yandex.ru/handbook/ml/article/optimizaciya-v-ml)
- [Gradient Descent Cheat Sheet](https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html)
- [Gradient Descent (MIT VisionBook)](https://visionbook.mit.edu/gradient_descent.html)

### 5. Открытые конспекты и материалы HSE

- [Конспект: `lecture01-intro.pdf` из курса Е. Соколова (2021)](https://github.com/esokolov/ml-course-hse/blob/master/2021-fall/lecture-notes/lecture01-intro.pdf)
- [Конспект: `lecture02-linregr.pdf` из курса Е. Соколова (2021)](https://github.com/esokolov/ml-course-hse/blob/master/2021-fall/lecture-notes/lecture02-linregr.pdf)
- [Конспект: `lecture01-intro.pdf` из курса Е. Соколова (2023)](https://github.com/esokolov/ml-course-hse/blob/master/2023-fall/lecture-notes/lecture01-intro.pdf)
- [Конспект: `lecture02-linregr.pdf` из курса Е. Соколова (2023)](https://github.com/esokolov/ml-course-hse/blob/master/2023-fall/lecture-notes/lecture02-linregr.pdf)
- [Конспект: `lecture05-linclass.pdf` из курса Е. Соколова (2023)](https://github.com/esokolov/ml-course-hse/blob/master/2023-fall/lecture-notes/lecture05-linclass.pdf)
- [Семинар по векторному дифференцированию](https://github.com/esokolov/ml-course-hse/blob/master/2023-fall/seminars/sem03-vector-diff.pdf)

### 6. Практика и библиотеки

- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
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
