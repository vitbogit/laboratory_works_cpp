# Лабораторные работы
Лабораторные работы на C++ для института (Laboratory works in C++ for the institute)

# lr_graphs - Графы:

Для взвешенного ориентированного графа реализовать:
- алгоритм поиска кратчайшего пути - алгоритм Дейкстры
- сделав тот же самый граф неориентированным, построить его остовное дерево минимальной стоимости - алгоритм Прима

Должны быть представлены промежуточные результаты.
По каждому кратчайшему пути указать предшествующие вершины.


# lr_queues - Очереди:
Программно реализовать очередь с приоритетами в виде линейного списка с символьными элементами.
Выполнение операций организовать с помощью меню:
- создание очереди;
- вывод на экран или в файл значений элементов очереди с их индексами (номерами) и   приоритетами;
- включение в очередь нового элемента;
- очистка очереди, 
- вывод элементов очереди с заданным значением приоритета.
После выполнения операций включения или выборки вывести новое содержимое очереди. 

Приоритеты задать произвольно в виде целых чисел. Наивысший приоритет у меньшего значения. Совпадение приоритетов - разрешено



# lr_lists - Списки:
Реализовать линейный список, состоящий из 20 элементов заданного типа. Интерфейс должен включать следующие операции:
- создание списка;
- вывод на экран и/или в файл значений элементов списка с их индексами (номерами);
- удаление списка,
- Поиск в списке элемента с максимальным значением с получением его номера в списке (повторное вхождение одного и того же значения разрешено)
- Включение нового элемента в начало списка.
- Удаление элемента из начала списка.
После выполнения операций включения или удаления вывести содержимое списка. Выполнение операций организовать с помощью меню.

# lr_search - Поиск:
Цель работы: изучить основные принципы работы алгоритмов поиска, исследовать их свойства: 
- алгоритм BLS - последовательный поиск (Better_Linear_Search);
- алгоритм SLS - быстрый последовательный поиск (Sentinel_Linear);
- алгоритм Т - последовательный поиск в упорядоченном массиве, в конце массива помещается фиктивная запись, значение которой намного больше значения ключа поиска;
- алгоритм В - бинарный поиск.
Задание
- Для алгоритмов BLS и SLS в качестве входного массива использовать одну и ту же последовательность значений (функция rand( )).
- Для алгоритмов Т и В – значения массива должны быть отсортированы по неубыванию, одна и та же последовательность чисел (можно использовать соответствующую функцию из первой лабораторной работы). 
- Оценить длительность поиска для различных значений размеров последовательностей (начиная с 10000 до 200000 элементов массива, провести измерения не менее, чем для 10 разных размерностей).
- Для каждой размерности рассматриваются случаи нахождения ключа поиска в начале, в середине и в конце массива.
- Для алгоритмов BLS и SLS кроме подсчета времени, необходимого для поиска, требуется определить сколько раз выполняются операции сравнения (сравнение ключа с элементом массива, а также в одном из этих двух алгоритмов добавляется подсчет сравнений при анализе индекса элемента массива в цикле… ).



