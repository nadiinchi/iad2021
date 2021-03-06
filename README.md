# «Введение в анализ данных»
## (майнор «Интеллектуальный анализ данных», НИУ ВШЭ, группа ИАД-2, 2021)

Семинарист: Надежда Чиркова (/nchirkova@hse.ru/, telegram @nadiinchi)

Ассистентки: Екатерина Кострыкина (@ekostrykina), Александра Штарёва (@hyarmaite)

[Страница курса на вики ВШЭ](http://wiki.cs.hse.ru/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B2_%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85_(%D0%BC%D0%B0%D0%B9%D0%BD%D0%BE%D1%80_%D0%98%D0%90%D0%94))

[Чат](https://t.me/joinchat/GnnT0omle1UE7HQ1)

[Zoom](https://zoom.us/j/97891126155?pwd=bXk0c2oxRm9jWUJuRUJtRDl1elB2QT09)

### Установка Anaconda и запуск Jupyter notebook
* Скачайте и установите дистрибутив для своей системы с [сайта](https://www.anaconda.com/download/). Дистрибутив содержит большинство необходимых нам библиотек.
* Откройте терминал/консоль (cmd на Windows или Terminal на MacOS) и напишите jupyter notebook. В браузере откроется интерфейс jupyter.

## Домашние задания
Домашние задания выдаются на 1 или 2 недели (мягкий дедлайн). По истечении дедлайна в течение нескольких дней есть возможность досдать задание со штрафными баллами: - 1 балл за каждый день просрочки до жесткого дедлайна. После жесткого дедлайна задание не принимается (совсем, даже при опоздании на одну секунду).

Задания нужно сдавать в Anytask: https://anytask.org/course/779. Инвайт: hHA6uvN. Для доступа к курсу необходимо зарегистрироваться в системе.

__Очень важно:__ Категорически запрещено пользоваться чужими решениями заданий (даже смотреть их), в том числе, размещенными в открытых источниках (если таковые обнаружатся). При обнаружении списывания выставляется 0 за задание (в случае списывания у одногруппника/однокурскника - ему/ей тоже), а также подается докладная записка в учебный офис. Проверка на списывание проводится и автоматическими средствами, и вручную.

* [Практическое задание 1](https://github.com/nadiinchi/iad2021/blob/main/materials/hw_sem1.ipynb). Мягкий дедлайн: 2 февраля, 23:59. Жесткий дедлайн: 9 февраля, 23:59.
* [Практическое задание 2](https://github.com/nadiinchi/iad2020/blob/master/materials/Homework2.ipynb).  Мягкий дедлайн: 21 февраля, 23:59. Жесткий дедлайн: 28 февраля, 23:59.
* [Практическое задание 3](https://github.com/nadiinchi/iad2021/blob/main/materials/homework3.ipynb). Мягкий дедлайн: 16 марта, 23:59. Жесткий дедлайн: 23 марта, 23:59.
* Опцинальные задания - можно выбрать одно любое: [А: общее по градиентному спуску](https://github.com/hse-ds/iad-intro-ds/blob/master/2021/homeworks/hw05_gd.ipynb) или [Б: наше по линейной классификации](https://github.com/nadiinchi/iad2020/blob/master/materials/sms_task.ipynb). За задание А дается 6 бонусных баллов (любые 6 баллов из задания), за задание Б дается 3 бонусных балла (полностью выполненное задание), сдать на оценку оба нельзя, но можно сдать второе без оценки, и его проверят. Мягкий дедлайн: 6 аперля, 23:59. Жесткий дедлайн: 10 апреля, 23:59.
* [Практическое задание 4](https://github.com/hse-ds/iad-intro-ds/tree/master/2021/homeworks/hw06-text). Мягкий дедлайн 23 апреля 23:59, жёсткий дедлайн 28 апреля 23:59. Также в рамках этого домашнего задания можно поучаствовать в [соревновании](https://www.kaggle.com/c/avito-category-prediction/overview).
За соревнование баллы только бонусные, дедлайн 15 мая.
* [Практическое задание 5](https://github.com/nadiinchi/iad2020/blob/master/materials/homework4_compositions.ipynb). Мягкий дедлайн 31 мая 23:59. Жесткий дедлайн 7 июня 23:59. Вместо этого задания можно выполнить [общее задание](https://github.com/hse-ds/iad-intro-ds/tree/master/2021/homeworks/hw07-trees-rf), но есть несколько небольших оговорок: (1) вы его сдаете вместе с общим дедлайном, т. е. 27 мая 23:59; (2) если вы выбрали его, то и следующее задание вы выполняете общее, а не наше; (3) полное выполнение задания означает набор 14.5 баллов (как у всех групп).
* [Практическое задание 6](https://github.com/nadiinchi/iad2020/blob/master/materials/hw_leafs.ipynb). Дедлайн: 17 июня (сразу мягкий и жесткий). Если в качестве задания 5 вы выполняли общее задание, но и 6-е выполняете общее с общим дедлайном.

## Проверочные
Раз в несколько семинаров проводится проверочная на знание материала лекций (и иногда семинаров). Строго рекомендуется повторять материал лекций перед проверочными!

## Материалы семинаров:
*Семинар 1-2.* Numpy + Python reminder.
* [Ноутбук с семинара по Numpy и Matplotlib](https://github.com/nadiinchi/iad2021/blob/main/materials/Numpy%202021.ipynb)
* [Ноутбук-туториал по numpy](https://github.com/nadiinchi/HSE_minor_DataAnalysis_seminars_iad16/blob/master/materials/Sem2_NumPy.ipynb)
* [Англоязычный подробный туториал по numpy](http://nbviewer.jupyter.org/github/Atlas7/scipy-tentative-numpy-tutorials/blob/master/tentative-numpy-tutorial.ipynb)

*Семинар 3.* Pandas.
* [Ноутбук с семинара](https://github.com/nadiinchi/iad2021/blob/main/materials/Pandas_seminar.ipynb)
* [Подробный ноутбук-туториал про pandas](https://github.com/nadiinchi/HSE_minor_DataAnalysis_seminars_iad16/blob/master/materials/Seminar3_pandas.ipynb)
* [Лекция на Курсере про pandas - 1](https://www.coursera.org/learn/mathematics-and-python/lecture/rcjAW/pandas-data-frame)
* [Лекция на Курсере про pandas - 2](https://www.coursera.org/learn/mathematics-and-python/lecture/lsXAR/pandas-indieksatsiia-i-sieliektsiia)
* [Официальная документация pandas - подробнейшие туториалы на английском](http://pandas.pydata.org/pandas-docs/stable/10min.html)

*Семинар 4.* kNN, Scikit-learn.
* [Ноутбук с семинара](https://github.com/nadiinchi/iad2021/blob/main/materials/Sklearn_2021.ipynb)
* [Конспект семинара](https://github.com/nadiinchi/iad2021/blob/main/materials/knn.pdf)
* [Документация sklearn](http://scikit-learn.org/stable/index.html)
* [Ноутбук Евгения Ковалева про kNN](https://github.com/nadiinchi/iad2020/blob/master/materials/sem05_knn.ipynb)

*Семинар 5.* Классы в Python и продолжение Scikit-learn
* [Ноутбук с семинара](https://github.com/nadiinchi/iad2021/blob/main/materials/Classes.ipynb)
* [Ноутбук про классы и sklearn - конспект семинара](https://github.com/nadiinchi/iad2019/blob/master/materials/Seminar_sklearn.ipynb)

*Семинар 6.* Линейная регрессия
* [Записи с доски](https://github.com/nadiinchi/iad2021/blob/main/materials/Whiteboard%5B3%5D.pdf)
* [Ноутбук с семинара](https://github.com/nadiinchi/iad2021/blob/main/materials/LinReg.ipynb)
* [Задачи](https://github.com/nadiinchi/iad2021/blob/main/materials/Whiteboard%5B3%5D.pdf)

*Семинар 7.* Трехмерная геометрия и градиентный спуск
* [Ноутбук для семинара](https://github.com/nadiinchi/iad2020/blob/master/materials/grads_students.ipynb)
* [Решение семинара](https://github.com/nadiinchi/iad2020/blob/master/materials/grads.ipynb)

*Семинар 8.* Метрики качества бинарной классификации
* [Конспект семинара](https://github.com/nadiinchi/iad2021/blob/main/materials/metrics.ipynb)
* [Ноутбук с ROC-кривой и PR-кривой](https://github.com/nadiinchi/iad2021/blob/main/materials/ROC_PR_curves.ipynb)

*Семинар 9.* Линейная классификация
* [Небольшое практическое задание](https://github.com/nadiinchi/iad2021/blob/main/materials/ROC_PR_curves_continued_small_task.ipynb)

*Семинар 10.* Линейные модели для анализа текстов
* [Конспект с заданием](https://github.com/nadiinchi/iad2020/blob/master/materials/sem_texts_students.ipynb)
* [Конспект с решением](https://github.com/nadiinchi/iad2020/blob/master/materials/sem_texts_solution.ipynb)

*Семинар 11. * Многоклассовая линейная классификация
* [Теоретический конспект](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture06-linclass.pdf)

*Семинар 12. * Решающие деревья
* [Конспект семинара](https://github.com/nadiinchi/iad2020/blob/master/materials/trees.pdf)
* [Практическое задание](https://github.com/nadiinchi/iad2020/blob/master/materials/trees_practice_students1.ipynb)

*Семинар 13. * Композиции алгоритмов: блендинг, бэггинг, случайный лес
* [Практическое задание](https://github.com/nadiinchi/iad2020/blob/master/materials/trees_practice_students2.ipynb)
* [Конспект](https://github.com/nadiinchi/iad2020/blob/master/materials/compositions.ipynb)

*Семинар 14.* Бустинг: теория

*Семинар 15.* Бустинг, практика
* [Ноутбук про увеличение числа деревьев](https://github.com/nadiinchi/iad2021/blob/main/materials/rf_gb_num_trees.ipynb)
* [Ноутбук про различные реализации градиентного бустинга](https://github.com/nadiinchi/iad2021/blob/main/materials/sem15_boostings_part2.ipynb)
* [Практическое задание (самостоятельная упрощенная реализация бустинга)](https://github.com/nadiinchi/iad2021/blob/main/materials/handmade_boosting_task.ipynb)

*Семинар 16.* Визуализация данных и генерация признаков
* [Презентция](https://github.com/nadiinchi/iad2021/blob/main/materials/%D0%9F%D1%80%D0%B5%D0%B7%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%D0%B8%D0%B7%D1%83%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.pdf)
* [Ноутбук](https://github.com/nadiinchi/iad2021/blob/main/materials/sem_part1_students.ipynb)

*Семинар 17.* Понижение размерности, кластеризация.
* [Ноутбук по реализации кластеризации](https://github.com/nadiinchi/iad2020/blob/master/materials/Sem_clustering.ipynb)

## Полезные ссылки
* [Курс на Отрытом образовании по машинному обучению (Евгений Соколов)](https://openedu.ru/course/hse/INTRML/)
* [Специализация по анализу данных на coursera.org](https://ru.coursera.org/specializations/machine-learning-data-analysis)
* [Видеозаписи курса лекций К. В. Воронцова](https://yandexdataschool.ru/edu-process/courses/machine-learning)
* [Лекции Andrew Ng на coursera.org](https://www.coursera.org/learn/machine-learning): практические задания на языке MATLAB/Octave
* [Вводный курс К. В. Воронцова на coursera.org](https://www.coursera.org/learn/introduction-machine-learning)
* [https://www.dataquest.io](https://www.dataquest.io): сайт с интерактивными заданиями по Python для анализа данных
* [Pattern Recognition and Machine Learning by C. Bishop](http://www.rmki.kfki.hu/~banmi/elte/Bishop%20-%20Pattern%20Recognition%20and%20Machine%20Learning.pdf)
* [James, Witten, Hastie, Tibshirani — An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf)

За прохождение курсов на coursera.org не обязательно платить: можно попросить материальную помощь или воспользоваться подпиской университета (для курсов университета).

