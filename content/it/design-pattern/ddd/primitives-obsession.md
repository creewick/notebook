---
title: Одержимость примитивами
---
Часто лучше описать свой собственный класс [[it/design-pattern/ddd/entity-type/value-object|Value object]], чем описывать данные примитивными типами

#### Плохо
```c-sharp
int Delay { get; }
int DelayInSeconds { get; }
```

#### Хорошо
```c-sharp
TimeSpan Delay { get; }
```

#### Кандидаты на Value object
- Временной интервал
- Адрес проживания
- IP-адрес
- Сумма денег с валютой
- Геометрические примитивы
	- Point
	- Segment
	- Line
	- Polygon
- ФИО