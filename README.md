# Задание: <br> Необходимо написать код на Python и оценить сложность алгоритма О(N).
## Написать программу, которая принимает строку от пользователя и выводит количество символов в этой строке.

# Решение:


## Пояснения.

Задача решена 3-мя способами. 
1. С использованием стандартной функции len. В проекте функция simple_count
2. С предварительным преобразованием строки в массив. В проекте функция count_by_symbol.
3. Получение минимальной посимвольной статистики. В проекте функция get_str_statistic. <br>
   Статистика включает следующие сведения: 
   - общее количество символов;
   - количество уникальных символов;
   - символ;
   - количество повторений символа в строке;
   - процент повторений символа в строке.

## Оценка сложности алгоритма.
1. При решении 1-м и 2-м способами сложность будет линейной и зависеть только от длинны массива.
2. При решении 3-м способом оценить сложность затруднительно, но предполагаю, что за счет алгоритмов оптимизации numpy сложность будет меньше зависеть от количества символов в строке.