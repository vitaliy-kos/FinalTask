
# FinalTask - итоговая контрольная работа
## <b style="color:#265f36">Задача</b>
Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
### Примеры результата:
```
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []
```

## <b style="color:#265f36">Описание алгоритма решения:</b>

Для решения поставленной задачи объявляется у пользователя спрашивается желаемый размер массива - количество значений на входе. После этого в методе **_CreateAndFillArrayByUser_** создается массив и запрашиваются пользовательские значения строк для каждого элемента. После этого в консоль выводится получившийся массив значений и задается параметр **_stringLength_** который устанавливает значение длины строки для попадаения в результирующий массив. Программа обращается к методу **_FilterArrayLessLengthElem_** и передается исходный массив и параметр **_stringLength_**. Метод **_FilterArrayLessLengthElem_** вызывает метод **_CountArrayLessLengthElem_** для подсчета количества элементов короче указанной длины, после возвращания создается новый массив необходимой длины. В результате проверки на указанную длину  элементы укладываются в новый массив, после чего результирующий массив выводится в консоль.

## <b style="color:#265f36">Схема решения</b>
Графическое представление решения задачи представлено в папке [Scheme](/Scheme/FinalTask.png).
![Logo](/Scheme/FinalTask.png)

## <b style="color:#265f36">Программа</b>
Реализация программы по решению поставленной задачи находится в папке [FinalTask/Program.cs](FinalTask/Program.cs)