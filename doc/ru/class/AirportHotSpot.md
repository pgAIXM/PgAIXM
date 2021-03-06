AirportHotSpot
====
Источник: [AIXM](https://extranet.eurocontrol.int/http://webprisme.cfmu.eurocontrol.int/aixmwiki_public/bin/view/AIXM/Class_AirportHotSpot)

Тип: Feature

Области на аэродромной территории, где когда-либо случилось ранее или имеется потенциальный риск столкновения или несанкционированного выезда на ВПП, и где требуется повышенное внимание пилотов/водителей.

## Атрибуты

##### uuid

##### uuidElevatedSurface
Ссылка на: ElevatedSurface (uuid)

Ссылка на геометрию объекта.

#### uuidAirportHeliport
Ссылка на: AirportHeliport (uuid)

Ссылка на аэродром.

##### designator
Тип данных: TextNameType

Закодированный идентификатор, которым горячая точка (hot spot) помечена на картах аэропорта.

##### instruction
Тип данных: TextInstructionType

Действие, которое должен предпринять экипаж и/или водитель транспортного средства при приближении к горячей точке.


## Связи

### Один к одному:

- O ElevatedSurface

### Один ко многим:

- O ~~Note~~

### Многие ко многим:

- отсутствуют

### Многие к одному:

- F AirportHeliport
