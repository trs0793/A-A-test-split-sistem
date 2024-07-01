# A-А-test, split sistem (English)
### 1) Objective and Task Condition:

We need to simulate as if we conducted 10,000 A/A tests. In each iteration, we should create non-repeating subsamples of 500 users from two experimental groups. Compare these subsamples using a t-test. Construct a histogram of the distribution of the resulting 10,000 p-values. Calculate the percentage of p-values that are less than or equal to 0.05.

### 2) Tools Used During the Project:
- Python (libraries: Pandas, Numpy, Seaborn, Matplotlib, Scipy.stats, pandahouse)
- SQL query in ClickHouse

### 3) Result:

After conducting the test, I determined that in 4.81% of cases, there were statistically significant differences between the 2nd and 3rd groups (p-value < 0.05). Therefore, the splitting system works correctly.


# A-А-test, split sistem (Russian)
### 1)Цель и условие задачи:

 Необходимо сделать симуляцию, как будто мы провели 10000 А/А-тестов. На каждой итерации нужно сформировать подвыборки без повторения в 500 юзеров из двух экспериментальных групп. Провести сравнение этих подвыборок t-testом. Построить гистограмму распределения получившихся 10000 p-values. Посчитать, какой процент p values оказался меньше либо равен 0.05

 ### 2)Во время выполнения проекта я применял следующе инструменты:
 - Python (библиотеки Pandas, Numpy, Seaborn, Matplotlib, Scipy.stats, pandahouse).
 - SQL-запрос в ClickHouse

 ### 3)Результат:
   
После проведенного мной теста, я определил, что в 4.81% случаев получались статистические значимые различия между 2 и 3 группой (p_value < 0.05). Поэтому система сплитования работает корректно.
