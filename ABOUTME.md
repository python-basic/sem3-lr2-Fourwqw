### Формулеровка задания от преподавателя
Заголовок 2 уровня (имя или никнейм).
Маркированный список с 2-3 профессиональными компетенциями в айти-сфере (например: Word, Adobe Photoshop, язык программирования Swift).
Ссылка на портфолио (GitHub Pages или standalone-блог на отдельном сайте, например http://nickzhukov.ru).
Мотивирующая вас изображение или фотография (встроить в документ, чтобы отображалась как картинка). В качестве источника можно использовать сайт https://unsplash.com

# Решение

## Кузнецов Антон

-C++(Basic level)
-PascalABC
-github pages
[Test](https://github.com/python-basic/sem3-lr2-Fourwqw/edit/master/ABOUTME.md)
![название](1c2127a10a120e1f1f6b19dd25291b73.png "Ttitle is optional")

### Код решения най Python

```python
"""
		Кузнецов Антон Денисович 
		ИВТ 1.1, 2 курс
		Задание: вычисление площади треугольника по формуле Герона
"""
import math

def geron_sq(a,b,c):
	"""
		Функция вычисляет площадь треугольника по трем сторонам.


	"""
	p = int((a + b + c) / 2)
	res = p * math.sqrt((p - a) * (p - b) * (p -c))
	return res

def main():
	"""
		Функция всех функций
		
	"""
	a = int(input("Введите сторону a:"))
	b = int(input("Введите сторону b:"))
	c = int(input("Введите сторону c:"))
	print(geron_sq(a, b, c))


main()
input()
```
