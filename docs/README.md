# **Документация проекта Geometric Lib**

### Проект представляет собой библеотеку на языке Python для вычислений площади и периметра базовых фигур (круг, квадрат, прямоугольник, треугольник)

## **Описание функций**

### *Вычисление периметра:*

#### Circle: P = 2πR
#### Rectangle: P = 2a + 2b
#### Square: P = 4a
#### Triangle P = a + b + c

### *Вычисление площади:*

#### Circle: S = πR²
#### Rectangle: S = ab
#### Square: S = a²
#### Triangle: S = ah/2

# **Примеры вызова функций**
## **Площадь**
### circle.py
### area(6)
### Результат: 113.04
---
### rectangle.py
### area(5, 6)
### Результат: 30
---
### square.py
### area(12)
### Результат: 144
---
### triangle.py
### area(12, 6)
### Результат: 36
---
## **Периметр**

### circle.py
### perimeter(6)
### Результат: 37.68
---
### rectangle.py
### perimeter(5, 6)
### Результат: 22
---
### square.py
### perimeter(16)
### Результат: 256
---
### triangle.py
### perimeter(9, 16, 25)
### Результат: 50

# **История изменения проекта**

- `f2ba386` clear README.md
- `7c5d9b9` add comments
- `e879e6c` added triangle.py and fixed rectangle.py
- `3a8bfcc` add new file rectangle.py
- `d078c8d` (origin/main, origin/HEAD, main) L-03: Docs added
- `8ba9aeb` L-03: Circle and square added
