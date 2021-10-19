## Task 3. Triangles sorted by area.

Разработать консольную программу, выполняющую вывод треугольников в порядке убывания их площади. После добавления каждого нового треугольника программа спрашивает, хочет ли пользователь добавить ещё один. Если пользователь ответит “y” или “yes” (без учёта регистра), программа попросит ввести данные для ещё одного треугольника, в противном случае – выводит результат в консоль.

•	Расчёт площади треугольника должен производится по формуле Герона.
•	Каждый треугольник определяется именем и длинами его сторон. 
Формат ввода (разделитель - запятая): 
<имя>, <длина стороны>, <длина стороны>, <длина стороны>
•	Приложение должно обрабатывать ввод чисел с плавающей точкой.
•	Ввод должен быть нечувствителен к регистру, пробелам, табам.
•	Вывод данных должен быть следующем примере:
```
============= Triangles list: ===============
1. [Triangle first]: 17.23 сm
2. [Triangle 22]: 13 cm
3. [Triangle 1]: 1.5 cm
```

#### Eg.
```
Input triangle info: <name>, <sideA>, <sideB>, <sideC>
tr1, 1, 2, 1.5
>> Wish to add another triangle Yes/No?
y
Input triangle info: <name>, <sideA>, <sideB>, <sideC>
tr2, 2, 2, 2
>> Wish to add another triangle Yes/No?
y
Input triangle info: <name>, <sideA>, <sideB>, <sideC>
tr3, 1.55, 0.6, 1
>> Wish to add another triangle Yes/No?
n
=========Triangles list:=============
1. [tr2]: 1.732 cm2
2. [tr1]: 0.726 cm2
3. [tr3]: 0.149 cm2
```