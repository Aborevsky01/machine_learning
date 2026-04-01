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

Ниже собран рабочий план тем и соответствие материалов внутри репозитория. Блок со ссылками на записи оставлен в удобном для дальнейшего заполнения виде.

| № | Тема | Лекция | Семинар / практика | VK | YouTube |
| --- | --- | --- | --- | --- | --- |
| 1 | Введение в машинное обучение | [`01-course-overview-and-ml-intro.pdf`](lectures/01-course-overview-and-ml-intro.pdf) | [`practice-00-pandas-basics.ipynb`](seminars/practice-00-pandas-basics.ipynb) | TODO | [запись](https://youtu.be/-tz5KDMKd4E) |
| 2 | Линейная регрессия | [`02-linear-regression.pdf`](lectures/02-linear-regression.pdf) | [`practice-02-linear-regression-with-sklearn.ipynb`](seminars/practice-02-linear-regression-with-sklearn.ipynb), [`hw-02-linear-regression.ipynb`](homeworks/hw-02-linear-regression.ipynb) | TODO | [запись](https://www.youtube.com/watch?v=iNYUmd0-_UU&list=PLEwK9wdS5g0ohn4v-t8yaCOEAC0KT3EPf&index=3) |
| 3 | Градиентный спуск и оптимизация | [`03-gradient-descent-and-optimization.pdf`](lectures/03-gradient-descent-and-optimization.pdf) | [`practice-01-gradient-descent-warmup.ipynb`](seminars/practice-01-gradient-descent-warmup.ipynb), [`practice-01-gradient-descent-hands-on.ipynb`](seminars/practice-01-gradient-descent-hands-on.ipynb), [`practice-03-optimization-and-gradient-methods.ipynb`](seminars/practice-03-optimization-and-gradient-methods.ipynb) | TODO | TODO |
| 4 | Линейная классификация | [`04-linear-classification.pdf`](lectures/04-linear-classification.pdf) | [`practice-04-binary-linear-classification.ipynb`](seminars/practice-04-binary-linear-classification.ipynb), [`practice-05-linear-classifiers.ipynb`](seminars/practice-05-linear-classifiers.ipynb) | TODO | TODO |
| 5 | Метрики, регуляризация и валидация | [`05-metrics-regularization-and-validation.pdf`](lectures/05-metrics-regularization-and-validation.pdf) | [`practice-05-logreg-and-svm.ipynb`](seminars/practice-05-logreg-and-svm.ipynb), [`practice-06-probability-calibration.ipynb`](seminars/practice-06-probability-calibration.ipynb) | TODO | TODO |
| 6 | Метод опорных векторов | [`06-support-vector-machines.pdf`](lectures/06-support-vector-machines.pdf) | [`practice-05-logreg-and-svm.ipynb`](seminars/practice-05-logreg-and-svm.ipynb) | TODO | TODO |
| 7 | Решающие деревья | [`07-decision-trees.pdf`](lectures/07-decision-trees.pdf) | [`practice-07-decision-trees.ipynb`](seminars/practice-07-decision-trees.ipynb) | TODO | TODO |
| 8 | Ансамбли и случайный лес | [`08-ensembles-and-random-forest.pdf`](lectures/08-ensembles-and-random-forest.pdf) | [`practice-09-random-forest.ipynb`](seminars/practice-09-random-forest.ipynb) | TODO | TODO |
| 9 | Градиентный бустинг | [`09-gradient-boosting.pdf`](lectures/09-gradient-boosting.pdf) | [`practice-10-boosting-basics.ipynb`](seminars/practice-10-boosting-basics.ipynb) | TODO | TODO |
| 10 | Продвинутый бустинг и практические трюки | [`10-advanced-boosting.pdf`](lectures/10-advanced-boosting.pdf) | [`practice-11-advanced-boosting.ipynb`](seminars/practice-11-advanced-boosting.ipynb) | TODO | TODO |
| 11 | Работа с текстами и прикладные пайплайны | [`11-texts-and-applied-ml.pdf`](lectures/11-texts-and-applied-ml.pdf) | [`practice-08-text-classification.ipynb`](seminars/practice-08-text-classification.ipynb) | TODO | TODO |
| 12 | Ненаблюдаемое обучение и кластеризация | [`12-clustering.pdf`](lectures/12-clustering.pdf) | материал семинара будет добавлен отдельно | TODO | TODO |

## Домашние Задания

- [`hw-01-pandas-and-visualization.ipynb`](homeworks/hw-01-pandas-and-visualization.ipynb) - работа с `pandas`, табличными данными и базовой визуализацией;
- [`hw-02-linear-regression.ipynb`](homeworks/hw-02-linear-regression.ipynb) - признаки, линейные модели и регрессия.

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
- [Интуитивный видеоразбор по градиентному спуску](https://www.youtube.com/watch?v=IHZwWFHWa-w&t=779s&pp=ygURZ3JhZGllbnRzIGRlc2NlbnQ%3D)
- [Ещё один видеоразбор по оптимизации](https://www.youtube.com/watch?v=S5AGN9XfPK4)
- [Короткий видеоразбор по градиентному спуску](https://www.youtube.com/watch?v=qg4PchTECck)

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

При подготовке части материалов использовались открытые образовательные ресурсы и конспекты ФКН, включая материалы курса [Евгения Соколова](https://github.com/esokolov/ml-course-hse). Этот репозиторий не дублирует исходный курс, а собирает публичную версию именно ваших материалов в компактной и удобной структуре.
