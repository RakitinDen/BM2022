# Курс Байесовские методы анализа данных, ФТиАД 2022

### Где и когда
Занятия проходят по четвергам, 18:10 — 21:00, очно.

### Преподаватели
[Денис Ракитин](https://www.hse.ru/org/persons/190910999), [Тимофей Южаков](https://www.hse.ru/org/persons/542007389)

### Ссылки
[Здесь будет место для сдачи заданий]

### Правила выставления оценок
В курсе предусмотрено несколько форм контроля знания:
* Домашние работы (практика на Python/NumPy и теоретические задачи, две работы)
* Контрольная работа (тест) в середине модуля
* Экзамен (письменная работа) в конце модуля.

Итоговая оценка вычисляется на основе оценки за работу в семестре и оценки за экзамен:

O<sub>итоговая</sub> = 0.5 * О<sub>домашние задания</sub> + 0.2 * О<sub>контрольная работа</sub>  + 0.3 * О<sub>экзамен</sub>.

Оценка за домашнюю работу вычисляется как среднее по домашним заданиям. К итоговой оценке применяется арифметическое округление.

После занятий могут выдаваться необязательные теоретические или практические задания для самостоятельной работы. Эти задания не сдаются и не проверяются. Однако задачи из необязательных теоретических заданий могут встретиться в контрольной работе или экзамене (или похожие задачи). Необязательные практические задания выдаются для желающих дополнительно потренироваться в реализации изучаемых методов.

### Экзамен
[Вопросы к экзамену с прошлых лет](https://github.com/ftad/BM2020/blob/master/materials/BMMO_exam_2020_full.pdf)

Экзамен письменный,  работа состоит из теоретических вопросов из списка вопросов (возможны измененные формулировки) и теоретических задач. Продолжительность написания: 1 час 30 минут. На экзамене можно пользоваться одним листом размера А5 (половина стандартного А4), написанным от руки.

### Контрольная работа
В середине курса проводится контрольная работа в виде теста по материалам нескольких первых занятий. 
[Вопросы для подготовки с прошлых лет](https://github.com/ftad/BM2020/blob/master/materials/questions_KR.pdf)

### Правила сдачи домашних заданий

У домашнего задания есть два дедлайна: мягкий и жесткий. Жесткий дедлайн через неделю после мягкого. За сдачу после мягкого дедлайна применяется штраф -1 балл за каждый день просрочки. После жесткого дедлайна сдать работу нельзя.

При обнаружении плагиата оценки за домашнее задание обнуляются всем задействованным в списывании студентам.

### Материалы занятий

__Занятие 1. Введение в байесовские методы. Сопряженные распределения__
* [Презентация](https://github.com/nadiinchi/bm_mini_course_UCM/blob/master/Bayesian_methods_presentation.pdf)
* [Запись лекции](https://drive.google.com/file/d/1fMKEHK75WErpJWnFiesKfiOt-l2BOTId/view?usp=sharing)
* [Конспект семинара](https://drive.google.com/file/d/1VcbO2_XmawXnR7GsMGrsG7vzM7Cv1JES/view?usp=sharing)
* [__Задание для самостоятельной работы__](https://github.com/ftad/BM2018/blob/master/homeworks/homework2.pdf) (кроме пункта 6)

__Занятие 2. Байесовская линейная регрессия__
* [Презентация](https://github.com/ftad/BM2020/blob/master/materials/presentation_linear_FTAD.pdf)
* [Запись лекции, часть 1](https://drive.google.com/file/d/1fOGQbN6jlgk3j1xIzeIWT3iT5P0NNd7C/view?usp=sharing)
* [Запись лекции, часть 2](https://drive.google.com/file/d/1Z2HFmnhTsx3azgjVnnUIEd7d9-vwsg07/view?usp=sharing)

__Занятие 3. Вариационный вывод и байесовские нейронные сети (с прошлого года)__
* [Презентация 1 (слайды 82-102)](https://github.com/nadiinchi/bm_mini_course_UCM/blob/master/Bayesian_methods_presentation.pdf)
* [Презентация 2](https://github.com/ftad/BM2020/blob/master/materials/presentation_bnn_ftad.pdf)
* [__Задание для самостоятельной работы__](https://github.com/nadiinchi/mlhep2019/blob/master/notebooks/day-4/Bayesian/SparseVD_assignment.ipynb)

__Занятие 4. Методы Markov Chain Monte Carlo__
* [Презентация](https://github.com/ftad/BM2020/blob/master/materials/presentation_MCMC_ftad.pdf)
* [Запись лекции](https://drive.google.com/file/d/1-394fJ3pjQsOWNWaVo3s0A4cUQi-BwHc/view?usp=sharing)
* Видео, использованные в конце лекции (динамика Ланжевена): [первое](https://www.youtube.com/watch?v=1xBKlnMjO-c), [второе](https://www.youtube.com/watch?v=cVn0kru3hL8)
* [__Задание для самостоятельной работы__](https://github.com/ftad/BM2020/blob/master/materials/homework_BNN.pdf)

### Задания

### Полезные материалы
Книги:
* Barber D. [Bayesian Reasoning and Machine Learning.](http://www0.cs.ucl.ac.uk/staff/d.barber/brml/) Cambridge University Press, 2012.
* Murphy K.P. Machine Learning: A Probabilistic Perspective. The MIT Press, 2012.
* Bishop C.M. [Pattern Recognition and Machine Learning.](http://research.microsoft.com/en-us/um/people/cmbishop/prml/) Springer, 2006. 
* Mackay D.J.C. [Information Theory, Inference, and Learning Algorithms.](http://www.inference.phy.cam.ac.uk/mackay/itila/book.html) Cambridge University Press, 2003. 
* Tipping M. [Sparse Bayesian Learning.](http://www.jmlr.org/papers/volume1/tipping01a/tipping01a.pdf) Journal of Machine Learning Research, 1, 2001, pp. 211-244. 
* Шумский С.А. [Байесова регуляризация обучения.](http://www.niisi.ru/iont/ni/Library/School-2002/Shumsky-2002.pdf) В сб. Лекции по нейроинформатике, часть 2, 2002.

Простые и удобные [заметки](http://cs.nyu.edu/~roweis/notes.html) по матричным вычислениям и свойствам гауссовских распределений.

[Памятка](http://statistics.zone/) по теории вероятностей.


### P.S.

Курс разработан [Надеждой Чирковой](https://github.com/nadiinchi). Материалы прошлых лет можно найти [здесь](https://github.com/ftad/BM2021).
