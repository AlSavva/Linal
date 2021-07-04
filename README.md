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
   
 __2.__ Найти сумму и произведение матриц <img src = "https://render.githubusercontent.com/render/math?math=A=\begin{pmatrix}1 & -2\\3 & 0\end{pmatrix}"> и <img src = "https://render.githubusercontent.com/render/math?math=B=\begin{pmatrix}4 & -1\\0 & 5\end{pmatrix}">.
    
