# weter62-63

Параграф 62
1. Массив — это структура данных, используемая в компьютерном программировании и информатике. Это набор элементов (часто одного и того же типа), хранящихся в смежных ячейках памяти. 3

Зачем нужны массивы:
   - Для хранения данных.
   - Для реализации алгоритмов.
   - Для обработки данных.
   - Для научных и математических вычислений.

2. Объявление массивов необходимо, чтобы упростить работу с набором однотипных данных.

3. Массивы в Python можно объявить с помощью встроенного модуля array или используя списки (list).

4. Элементы массива расположены рядом, потому что память выделяется непрерывной областью.

5. Чтобы обратиться к элементу массива в Python, нужно написать имя массива, за которым следуют квадратные скобки.

6. Могут начинаться с 0, но не с -5.

7. Размер массива лучше вводить как константу, а не как число, для повышения универсальности программы.

8. Для ввода массива можно использовать цикл с параметром, вводя значение каждого элемента с клавиатуры.

9. array = [random.randint(100, 200) for _ in range]

Паргарф 63
1. При поиске индекса максимального элемента не нужно хранить само значение максимального элемента, потому что по индексу элемента можно всегда определить его значение.

2. Реверс массива — это перестановка его элементов в обратном порядке: первый элемент становится последним, а последний — первым.

3. Некоторые ошибки, которые чаще всего делают начинающие программисты при программировании реверса массива:

   - Программирование обычного массива без реверса. Ошибку можно допустить в любом месте, даже не заметив этого. 
   - Цикл по всему массиву. В результате каждое значение перемещается два раза и оказывается на своём исходном месте. 
   - Забывание о том, что массивы могут быть как чётной, так и нечётной длины.
  
4. Некоторые проблемы, которые могут возникать при циклическом сдвиге массивов вправо:

   - Ошибочный результат из-за повторяющихся элементов. Если в списке есть повторяющиеся элементы, то метод вернёт индекс первого вхождения элемента, а не индекс текущего элемента. Это может привести к неправильному порядку элементов. 
   - Неправильное индексирование и выход за границы массива. Попытка доступа к элементу массива с индексом, превышающим допустимый диапазон, может привести к непредсказуемому поведению программы и аварийному завершению. 
   - Дублирование элементов. Оно возможно, если не сохранить и не использовать временную переменную для старых значений.
  
5. Массив заработает

6. Чтобы определить, что элемент не найден при использовании определённого алгоритма поиска, можно проверить, что весь массив просмотрен. Если это так, значит, в исходном массиве нет элемента, удовлетворяющего условию задачи.

7. Выход за границы массива — это обращение к элементу с индексом, который не существует в массиве.

8. Один из алгоритмов отбора части элемента одного массива в другой на примере языка Python: 14

   - Создать пустой список. 
   - Перебрать все элементы исходного массива и, если очередной элемент нужен, добавить его в новый список с помощью метода append.
