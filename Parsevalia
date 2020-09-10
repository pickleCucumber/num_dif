from random import randint
from numpy import fftn, ifftn
N = 100  #% количество отсчетов
x = randint(1,N)  #% нормальное распределение
Et = sum(x**2)
print('Энергия сигнала во временной области:', Et)

X = fftn(x)
Ew = 1/N * sum(abs(X**2))
print('Энергия сигнала в частотной области:', Ew)

y = ifftn(X)
Etn = sum(y**2)
print('Энергия сигнала во временной области:', Etn)
