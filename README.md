# chess-python

Дано координати поля шахової дошки x та  y  (цілі числа в діапазоні 1-8). Враховуючи, що ліве нижнє поле дошки (1,1) є чорним,   перевірити істинність висловлення "поле з координатами (x,y) біле".
Код та результат:

def taskEight(x1, y1, x2, y2):
  check = (x1 == x2) or (y1 == y2) or (y1 - x1 == y2 - x2) or (y1 + x1 == y2 + x2)
   if check:         
    print('ферзь за один хід може перейти з поля (x1, y1) на поле (x2, y2)')     
   else:         
    print('ферзь за один хід не може перейти з поля (x1, y1) на поле (x2, y2)')
