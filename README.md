# chess-python
def taskEight(x1, y1, x2, y2):     check = (x1 == x2) or (y1 == y2) or (y1 - x1 == y2 - x2) or (y1 + x1 == y2 + x2)     if check:         print('ферзь за один хід може перейти з поля (x1, y1) на поле (x2, y2)')     else:         print('ферзь за один хід не може перейти з поля (x1, y1) на поле (x2, y2)')
