---
title: "Настройка ДЦ"
permalink: /docs/disp/setting/
toc: true
---

## Создание диспетчерского центра

### ДЦ типа "Авто"
**Назначение** - дипетчирование перевозок, связанных с операциями на автомобильной части маршрута.

1.  Используем пункт меню *Диспетчирование* > *Настройка ДЦ*
2.  Добавляем новый ДЦ, где заполняем:
-   *Наименование* - Название, отображаемое в списке ДЦ
-   *Префикс* - Сокращенное наименование ДЦ
-   *Тип* - Авто
-   *Общий* - Не устанавливаем, если применяется разделение перевозок по ДЦ с учетом транспортных пунктов (назначение конкретного ДЦ для операции в перевозке)

**Важно!** **Общий** следует установить, если необходимо **автоматическое** отображение перевозки в ДЦ без учета транспортных пунктов в перевозке

3.  Жмем кнопку *Применить*
4.  Добавлем сотрудников, имеющих доступ к ДЦ на вкладке *Ответственные*
5.  Добавляем технологические операции, которые подбираются для ДЦ из перевозок, на вкладке *Операции*
6.  Добавляем технологические пункты на вкладке *Транспортные пункты*:
-   Если установлен флаг *Общий*, то транспортные пункты не учитываются для отбора перевозок в ДЦ
-   Если **не** установлен флаг *Общий*, то указанные транспортные пункты учитываются при подборе ДЦ для операции в перевозке

### ДЦ типа "ЖД"
**Назначение** - отображение перевозок, связанных с прибытием/отправлением по станции.

1.  Используем пункт меню *Диспетчирование* > *Настройка ДЦ*
2.  Добавляем новый ДЦ, где заполняем:
-   *Наименование* - Название, отображаемое в списке ДЦ
-   *Префикс* - Сокращенное наименование ДЦ
-   *Тип* - ЖД
-   *Фильтр* - задаем вариант фильтра по станциям

3.  Жмем кнопку *Применить*
4.  Добавлем сотрудников, имеющих доступ к ДЦ на вкладке *Ответственные*
5.  Добавляем станции на вкладке *Станции* - указанные станции применяются для отбора перевозок с учетом указанного параметра в поле *фильтр*:
-   Станция отправления
-   Станция назначения
-   Обе станции