AltimeterSource
====
Источник: [AIXM](https://extranet.eurocontrol.int/http://webprisme.cfmu.eurocontrol.int/aixmwiki_public/bin/view/AIXM/Class_AltimeterSource)

Тип: Feature

Прибор, который измеряет и показывает высоту, на которой расположен объект (например, самолет).

## Атрибуты

##### uuid

##### isRemote
Тип данных: CodeYesNoType

Код указывающий на то, какой высотомер: удаленный или локальный.

##### isPrimary
Тип данных: CodeYesNoType

Код указывающий на то, какой высотомер: главный или вторичный.

## Связи

### Один к одному:

- отсутствуют

### Один ко многим:

- O AltimeterSourceStatus
- O ~~ApproachCondition~~
- O ~~Note~~

### Многие ко многим:

- F AirportHeliport

### Многие к одному:

- отсутствуют
