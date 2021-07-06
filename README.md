# Курс линейной алгебры университета GeekBrains.  

## Урок 1. Линейное пространство.  

## Практическое задание к уроку 1. (Часть 1).
1. Исследовать на линейную зависимость:  <img src = "https://render.githubusercontent.com/render/math?math=f_{1}(x)=e^{x}, f_{2}(x)=1, f_{3}(x)=x%2B1, f_{4}(x)=x-e^{x}">  
2. Исследовать на линейную зависимость:  <img src = "https://render.githubusercontent.com/render/math?math=f_{1}(x)=2, f_{2}(x)=x, f_{3}(x)=x^{2}, f_{4}(x)=(x%2B1)^{2}">  
3. Найти координаты вектора <img src = "https://render.githubusercontent.com/render/math?math=x = (2, 3, 5)\in \mathbb{R}^{3}"> в базисе <img src = "https://render.githubusercontent.com/render/math?math=b_{1}=(0, 0, 10)">, <img src = "https://render.githubusercontent.com/render/math?math=b_{2}=(2, 0, 0)">, <img src = "https://render.githubusercontent.com/render/math?math=b_{3}=(0, 1, 0)">.  
4. Найти координаты вектора <img src = "https://render.githubusercontent.com/render/math?math=3x^{2}-2x%2B2\in\mathbb{R}^{3}[x]">:  
а) в базисе <img src = "https://render.githubusercontent.com/render/math?math=1">, <img src = "https://render.githubusercontent.com/render/math?math=x">, <img src = "https://render.githubusercontent.com/render/math?math=x^{2}">;  
б) в базисе <img src = "https://render.githubusercontent.com/render/math?math=x^{2}">, <img src = "https://render.githubusercontent.com/render/math?math=x-1">, <img src = "https://render.githubusercontent.com/render/math?math=1">.  
5. Установить, является ли линейным подпространством:  
а) совокупность всех векторов трехмерного пространства, у которых по крайней мере одна из первых двух координат равна нулю;      
б) все векторы, являющиеся линейными комбинациями данных векторов <img src = "https://render.githubusercontent.com/render/math?math=\{u_{1}, u_{2}, \ldots, u_{n}\}">  

## Практическое задание к уроку 1. (Часть 2).  
1. Найти скалярное произведение векторов <img src = "https://render.githubusercontent.com/render/math?math=x, y \in \mathbb{R}">:  
а) <img src = "https://render.githubusercontent.com/render/math?math=x=(0,-3, 6),y=(-4, 7, 9)">;  
б) <img src = "https://render.githubusercontent.com/render/math?math=x=(7, -4, 0, 1),y=(-3, 1, 11, 2)">.  
2. Найти нормы векторов <img src = "https://render.githubusercontent.com/render/math?math=(4, 2, 4)"> и <img src = "https://render.githubusercontent.com/render/math?math=(12, 3, 4)"> и угол между ними.  
3. Будет ли линейное пространство евклидовым, если за скалярное произведение принять:  
а) произведение длин векторов;  
б) утроенное обычное скалярное произведение векторов?  
4. Какие из нижеперечисленных векторов образуют ортонормированный базис в линейном пространстве <img src = "https://render.githubusercontent.com/render/math?math=\mathbb{R}^{3}">:  
а) <img src = "https://render.githubusercontent.com/render/math?math=(1,0,0),(0,0,1)">;  
б) <img src = "https://render.githubusercontent.com/render/math?math=(1/\sqrt{2},-1/\sqrt{2},0),(1/\sqrt{2},1/\sqrt{2},0), (0,0,1)">;  
в) <img src = "https://render.githubusercontent.com/render/math?math=(1/2, -1/2, 0), (0, 1/2, 1/2), (0,0,1)">;  
г) <img src = "https://render.githubusercontent.com/render/math?math=(1,0,0),(0,1,0),(0,0,1)">?  

## Урок 2. Матрицы и матричные операции.  

## Практическое задание к уроку 2. (Часть 1).  
Все задания рекомендуется делать вручную, затем проверяя полученные результаты с использованием numpy.

__1.__ Установить, какие произведения матриц <img src = "https://render.githubusercontent.com/render/math?math=AB"> и <img src = "https://render.githubusercontent.com/render/math?math=BA"> определены, и найти размерности полученных матриц:

   а) <img src = "https://render.githubusercontent.com/render/math?math=A"> — матрица <img src = "https://render.githubusercontent.com/render/math?math=4\times 2">, <img src = "https://render.githubusercontent.com/render/math?math=B"> — матрица <img src = "https://render.githubusercontent.com/render/math?math=4\times 2">;
    
   б) <img src = "https://render.githubusercontent.com/render/math?math=A"> — матрица <img src = "https://render.githubusercontent.com/render/math?math=2\times 5">, <img src = "https://render.githubusercontent.com/render/math?math=B"> — матрица <img src = "https://render.githubusercontent.com/render/math?math=5\times 3">;
    
   в) <img src = "https://render.githubusercontent.com/render/math?math=A"> — матрица <img src = "https://render.githubusercontent.com/render/math?math=8\times 3">, <img src = "https://render.githubusercontent.com/render/math?math=B"> — матрица <img src = "https://render.githubusercontent.com/render/math?math=3\times 8">;
    
   г) <img src = "https://render.githubusercontent.com/render/math?math=A"> — квадратная матрица <img src = "https://render.githubusercontent.com/render/math?math=4\times 4">, <img src = "https://render.githubusercontent.com/render/math?math=B"> — квадратная матрица <img src = "https://render.githubusercontent.com/render/math?math=4\times 4">.  
   
 __2.__ Найти сумму и произведение матриц <img src="https://render.githubusercontent.com/render/math?math=%24A%3D%5Cbegin%7Bpmatrix%7D%0A1%20%26%20-2%5C%5C%20%0A3%20%26%200%0A%5Cend%7Bpmatrix%7D%24"> и <img src="https://render.githubusercontent.com/render/math?math=%24B%3D%5Cbegin%7Bpmatrix%7D%0A4%20%26%20-1%5C%5C%20%0A0%20%26%205%0A%5Cend%7Bpmatrix%7D%24">.  
 
 __3.__ Из закономерностей сложения и умножения матриц на число можно сделать вывод, что матрицы одного размера образуют линейное пространство. Вычислить линейную комбинацию <img src="https://render.githubusercontent.com/render/math?math=%243A-2B%2B4C%24"> для матриц <img src="https://render.githubusercontent.com/render/math?math=%24A%3D%5Cbegin%7Bpmatrix%7D%0A1%20%26%207%5C%5C%20%0A3%20%26%20-6%0A%5Cend%7Bpmatrix%7D%24">, <img src="https://render.githubusercontent.com/render/math?math=%24B%3D%5Cbegin%7Bpmatrix%7D%0A0%20%26%205%5C%5C%20%0A2%20%26%20-1%0A%5Cend%7Bpmatrix%7D%24">, <img src="https://render.githubusercontent.com/render/math?math=%24C%3D%5Cbegin%7Bpmatrix%7D%0A2%20%26%20-4%5C%5C%20%0A1%20%26%201%0A%5Cend%7Bpmatrix%7D%24">.  
 
 __4.__ Дана матрица <img src="https://render.githubusercontent.com/render/math?math=%24A%3D%5Cbegin%7Bpmatrix%7D%0A4%20%26%201%5C%5C%20%0A5%20%26%20-2%5C%5C%20%0A2%20%26%203%0A%5Cend%7Bpmatrix%7D%24">.
Вычислить <img src="https://render.githubusercontent.com/render/math?math=%24AA%5E%7BT%7D%24"> и <img src="https://render.githubusercontent.com/render/math?math=%24A%5E%7BT%7DA%24">.  

__5*.__ Написать на Python функцию для перемножения двух произвольных матриц, не используя NumPy.  

## Практическое задание к уроку 2. (Часть 2).  
__1.__ Вычислить определитель:

   a)

<img src="https://render.githubusercontent.com/render/math?math=%24%5Cbegin%7Bpmatrix%7D%0Asinx%20%26%20-cosx%5C%5C%20%0Acosx%20%26%20sinx%0A%5Cend%7Bpmatrix%7D%24">;

   б)
    
<img src="https://render.githubusercontent.com/render/math?math=%24%5Cbegin%7Bpmatrix%7D%0A4%20%26%202%20%26%203%5C%5C%20%0A0%20%26%205%20%26%201%5C%5C%20%0A0%20%26%200%20%26%209%0A%5Cend%7Bpmatrix%7D%24">;
    
   в)

<img src="https://render.githubusercontent.com/render/math?math=%24%5Cbegin%7Bpmatrix%7D%0A1%20%26%202%20%26%203%5C%5C%20%0A4%20%26%205%20%26%206%5C%5C%20%0A7%20%26%208%20%26%209%0A%5Cend%7Bpmatrix%7D%24">.


__2.__ Определитель матрицы <img src="https://render.githubusercontent.com/render/math?math=A"> равен <img src="https://render.githubusercontent.com/render/math?math=4">. Найти:

   а) <img src="https://render.githubusercontent.com/render/math?math=%24det(A%5E%7B2%7D)%24">;
    
   б) <img src="https://render.githubusercontent.com/render/math?math=%24det(A%5E%7BT%7D)%24">;
    
   в) <img src="https://render.githubusercontent.com/render/math?math=%24det(2A)%24">.
   
__3.__  Доказать, что матрица

<img src="https://render.githubusercontent.com/render/math?math=%24%5Cbegin%7Bpmatrix%7D%0A-2%20%26%207%20%26%20-3%5C%5C%20%0A4%20%26%20-14%20%26%206%5C%5C%20%0A-3%20%26%207%20%26%2013%0A%5Cend%7Bpmatrix%7D%24">
   
вырожденная.

__4.__ Найти ранг матрицы:

   а) <img src="https://render.githubusercontent.com/render/math?math=%24%5Cbegin%7Bpmatrix%7D%0A1%20%26%202%20%26%203%5C%5C%20%0A1%20%26%201%20%26%201%5C%5C%20%0A2%20%26%203%20%26%204%0A%5Cend%7Bpmatrix%7D%24">;

   б) <img src="https://render.githubusercontent.com/render/math?math=%24%5Cbegin%7Bpmatrix%7D%0A0%20%26%200%20%26%202%20%26%201%5C%5C%20%0A0%20%26%200%20%26%202%20%26%202%5C%5C%20%0A0%20%26%200%20%26%204%20%26%203%5C%5C%20%0A2%20%26%203%20%26%205%20%26%206%0A%5Cend%7Bpmatrix%7D%24">.
    
