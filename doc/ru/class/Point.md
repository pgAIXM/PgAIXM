Point
====
Источник: [AIXM](https://extranet.eurocontrol.int/http://webprisme.cfmu.eurocontrol.int/aixmwiki_public/bin/view/AIXM/Class_Point)

Тип: Object

Географическая точка с указанием точности измерения горизонтальных координат.

## Наследование

### Родительский класс для:
- O Elevated Point

## Атрибуты

##### id

##### latitude
Тип данных: latitude

Географическая широта точки.

##### longitude
Тип данных: longitude

Географическая долгота точки.

##### horizontalAccuracy
Тип данных: ValDistanceType

Точность измерения горизонтальных координат.

Разница между записанными горизонтальными координатами объекта и его реальным положением в той же системе координат, выражается как диаметр (или радиус?) окружности в который попадает реальное местоположение с вероятностью 95%.

## Связи

### Один к одному:

- F ~~DesignatedPoint~~
- C ~~SignificantPoint~~

### Один ко многим:

- O ~~Note~~

### Многие ко многим:

- отсутствуют

### Многие к одному:

- отсутствуют
