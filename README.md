# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП факультета ВМК МГУ, осенний семестр 2024/2025
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2024/2025"

<p align="center">
<img src="https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/kernel_trick.jpg" height=400pt>
</p>

:white_check_mark: **Курс сдается через систему [anytask](https://anytask.org/course/1125). Инвайт можете получить у преподавателя**


:white_check_mark: **Полезные ссылки:**

* Текущие связанные курсы
    * [Курс практикум на эвм](https://github.com/mmp-practicum-team/mmp_practicum_fall_2024)
    * [Общий курс по МЛ(COMING SOON)]()

* Материалы прошлых лет:
  * [Материалы древних времен](https://github.com/esokolov/ml-course-msu)
  * [Вышкинский аналог курса](https://github.com/esokolov/ml-course-hse)
  * [Курс лекций по ММРО 20/21 (в те времена он читался эксклюзивно для ММП)](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
  * [Общий курс по МЛ 21/22](https://github.com/MSU-ML-COURSE/ML-COURSE-21-22)
  * [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)
  * [Курс ММРО 20/21, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020)
  * [Курс ММРО 21/22, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021)
  * [Курс ММРО 22/23, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022)
  * [Курс ММРО 23/24, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2023)

# Правила выставления оценок

:white_check_mark: **По этому курсу (ММРО) в конце семестра будет экзамен**

Общая оценка по нему выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/formula.png)
, где 

* Check — 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs — min(5, 5 * <сумма баллов за лабораторные + конкурсы + теор. дз.> / <суммарный макс балл за (лабораторные + конкурсы + теор.дз) (без бонусов)>
* Exam — оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все (5)** _лабораторные работы (4) и теор. дз. (1)_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 4-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 3-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor — округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

:white_check_mark: **По курсу лекций в конце семестра будет зачет без оценки**

Для получения этого зачета вам необходимо сдать **не менее 3-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов))

# Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 5 сентября  | Семинар 1 | Введение в курс. Pandas. Разведочный анализ данных |  [Ноутбук с семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar1_pandas.ipynb) | [Легкая домашка на пандас](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/tree/main/Homework1)   |
| 12 сентября  | Семинар 2 | Метрическая парадигма машинного обучения. KNN. Проблемы метода и практические применения | [Конспект семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_2_KNN_konspekt.pdf) |  ¯\\\_(ツ)\_/¯ |
| 19 сентября  | Семинар 3 | Функциональные парадигмы машинного обучения. Линейная регрессия. Градиентный спуск. Sklearn. | [Конспект семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_3_linreg_konspekt.pdf)   [Ноутбук семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_3_linregr_notebook.ipynb) |  [Домашнее задание на линейную регрессию](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Homework2/homework-practice_02-linregr.ipynb) |
| 26 сентября | Семинар 4 | Векторное дифференцирование | [Конспект семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_4_MatVecDiff_2024.pdf) |  ¯\\\_(ツ)\_/¯ |
| 3 октября | Семинар 5 | Логистическая регрессия: оценивание вероятностей и вывод функционала, калибровка вероятностей |  [Конспект семинара](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_5_%D0%B2%D0%B5%D1%80%D0%BE%D1%8F%D1%82%D0%BD%D0%BE%D1%81%D1%82%D0%BD%D0%B0%D1%8F_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0_%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8_%D0%B2_%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%BC_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B8.pdf) | ¯\\\_(ツ)\_/¯ |
| 10 октября | Семинар 6 | Задача оптимизации. Теорема Каруша-Куна-Таккера. Решение задач. | [Теория](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_6_conditionat_optimization/%D0%A2%D0%B5%D0%BE%D1%80%D0%B8%D1%8F.pdf) [Задачи](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_6_conditionat_optimization/%D0%97%D0%B0%D0%B4%D0%B0%D1%87%D0%B8.pdf) [Обучение_Lasso_регрессии](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_6_conditionat_optimization/%D0%9E%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_Lasso_%D1%80%D0%B5%D0%B3%D1%80%D0%B5%D1%81%D1%81%D0%B8%D0%B8.pdf) | [Хардкорная домашка на дифференцирование](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Homework3/%D0%A2%D0%B5%D0%BE%D1%80%D0%B5%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5_%D0%B4%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B5_%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5.pdf) |
| 17 октября | Семинар 7 | Ядровые обобщения методов, задачи на ядра, аппроксимация ядер | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_7_%D1%8F%D0%B4%D1%80%D0%BE%D0%B2%D1%8B%D0%B5_%D0%BE%D0%B1%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%BE%D0%B2.pdf) |  ¯\\\_(ツ)\_/¯ |
| 24 октября | Семинар 8 | Метрики качества классификации, ROC-AUG | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2024/blob/main/Seminar_8_%D0%B1%D0%B8%D0%BD%D0%B0%D1%80%D0%BD%D0%B0%D1%8F_%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F_%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%BA%D0%B8.pdf) |  [Дз на классификацию (COMING SOON)]() |
| 31 октября | Семинар 9 | Разложение ошибки на смещение и разброс | [Cеминар](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture08-ensembles.pdf) |  ¯\\\_(ツ)\_/¯ |
| 7 ноября | Семинар 10 | Логическая парадигма машинного обучения. Решающее дерево. Вывод критериев информативности для деревьев. Реализация на практике. |  |  ¯\\\_(ツ)\_/¯ |
| 14 ноября | Семинар 11 | Вывод градиентного бустинга |  |  ¯\\\_(ツ)\_/¯ |
| 21 ноября | Семинар 12 | Почему градиентный бустинг так устроен |  |  ¯\\\_(ツ)\_/¯ |
| 28 ноября | Семинар 13 | Имплементации градиентного бустинга |  |  ¯\\\_(ツ)\_/¯ |
| 5 декабря | Семинар 14 | Бонусный семинар | |  ¯\\\_(ツ)\_/¯ |
