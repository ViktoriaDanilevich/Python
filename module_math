#1. Напишите программу, определяющую евклидово расстояние между двумя точками, координаты которых заданы.
import math
x1, y1, x2, y2 = float(input()), float(input()), float(input()), float(input())
num = ((x1-x2)**2) + ((y1-y2)**2)
p = math.sqrt(num)
print(p)

#2. Напишите программу, определяющую площадь круга и длину окружности по заданному радиусу R.
import math
r = float(input())
s = math.pi * math.pow(r, 2)
c = 2 * math.pi * r
print(s, c, sep='\n')

#3. На вход программе подаются два положительных действительных числа a и b​, каждое на отдельной строке. Программа должна вывести 4 числа (каждое на отдельной строке) – среднее арифметическое, геометрическое, гармоническое и квадратичное.
import math
a, b = float(input()), float(input())
arithmetic_mean = (a+b) / 2
geometric_mean = math.sqrt(a*b)
harmonic_mean = 2*a*b / (a+b)
quadratic_mean = math.sqrt ((a**2 + b**2)/2)
print(arithmetic_mean, geometric_mean, harmonic_mean, quadratic_mean, sep='\n')


#4. Напишите программу, вычисляющую значение тригонометрического выражения по заданному числу градусов x.
import math
x = float(input())
rad = math.radians(x)
sin = math.sin(rad)
cos = math.cos(rad)
tan = math.tan(rad)
res = sin + cos + tan**2
print(res)

#5. Даны три действительных числа a, b, c. Напишите программу, которая находит действительные корни квадратного уравнения.
import math
a, b, c = float(input()), float(input()), float(input())
d = math.pow(b, 2) - 4*a*c
if d<0:
    print('Нет корней')
elif d == 0:
    x = - (b/(2*a))
    print(x)
else:
    x1 = (-b - math.sqrt(d)) / (2*a)
    x2 = (-b + math.sqrt(d)) / (2*a)
    if x1<x2:
        print(x1, x2, sep='\n')
    else:
        print(x2, x1, sep='\n')

