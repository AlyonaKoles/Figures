# Figures — Transforming

### Пример вывода

```text
=== Начальные фигуры ===
Rect(x=2, y=2, width=4, height=2)
Circle(x=4, y=3, radius=2)
Square(x=2, y=2, side=4)

=== Перемещение ===
Rect(x=3, y=1, width=4, height=2)
Circle(x=6, y=4, radius=2)
Square(x=1, y=4, side=4)

=== Масштабирование x2 ===
Rect(x=1, y=0, width=8, height=4)
Circle(x=6, y=4, radius=4)
Square(x=-1, y=2, side=8)

=== Поворот по часовой стрелке на 90° вокруг (4, 3) ===
Rect(x=1, y=-2, width=4, height=8)
Circle(x=5, y=1, radius=4)
Square(x=3, y=0, side=8)

=== Поворот против часовой стрелки на 90° ===
Rect(x=1, y=0, width=8, height=4)
Circle(x=6, y=4, radius=4)
Square(x=-1, y=2, side=8)
```

## Структура

```text
src/
├── Figure.kt
├── Movable.kt
├── Transforming.kt
├── Geometry.kt
├── Rect.kt
├── Circle.kt
├── Square.kt
└── Main.kt
```
