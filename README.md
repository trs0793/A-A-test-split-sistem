# A-А-test, split sistem
### 1)Цель и условие задачи:

 Необходимо сделать симуляцию, как будто мы провели 10000 А/А-тестов. На каждой итерации нужно сформировать подвыборки без повторения в 500 юзеров из двух экспериментальных группы. Провести сравнение этих подвыборок t-testом. Построить гистограмму распределения получившихся 10000 p-values. Посчитать, какой процент p values оказался меньше либо равен 0.05

 ### 2)Во время выполнения проекта я применял следующе инструменты:
 - Python (библиотеки Pandas, Numpy, Seaborn, Matplotlib, Scipy.stats).

 ### 3)Результат:
   
 Так как метрика является колличественной переменной и у нас есть 2 группы которые планируем сравнивать по одному критерию, 
и распределение у нас ненормальное и колличество экспериментов мало, то  для сравнения используем BOOTSTRAP
Доверительные интервалы параметров двух групп перекрываются, поэтому мы принимаем нулевую гипотезу,
что разница между средней суммой  в тестовой и контрольной группе нет.

**Поэтому доказанно, что запускать новую механику оплаты на всех пользователей НЕ стоит!**
