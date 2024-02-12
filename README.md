# Базы данных лекции

#нужно сделать что-то в ворде на тему история баз данных  указать 3 источника

Почта Ирина александровна Озеркова: i.ozerekova@mgutu.ru указывать задане нруппу фамилию и тему

15.01.2024

#Основные_понятия 

| |информация| |
|-|-|-|
| | знания | данные|
| декларативные| процедурные| |
Информация - сведения о чём-либо
Инф сис - совокупность технических программных средств, обеспечивающих сбор, хранения, обработку, поиск и выдачу инф в задачах любой области
Предметная область - часть реального мира, данные о которой используются в инф сис
Данные - зафиксированные в какой-либо форме информация
Информационный объект - описание некоторой сущности предметной области

пользователь <=> инф сис <=> СУБД <=> БД

База данных - специальным образом организованная именованная совокупность данных о некоторой предметной области (сущности), которая отражает состояние объектов и их отношения в некоторой предметной области, обычно хранящаяся во внешней памяти компа
Структура данных - совокупность правил и ограничений, которые отражают связи, существующие между отдельным частями (элементами) данных
Обработка данных - совокупность задач, отражающих преобразование данных
Сис обработки данных - набор аппаратных и программных ср-в, осуществляющих выполнение задач обработки данных
Управление данными - весь круг операций с данными, которые необходимы для успешного функционирования системы данных
Метаданные - описание собственной структуры данных

СУБД (Сис управления базами данных) - это совокупность языковых и программных средств, которая позволяет выполнять все необходимые операции с базой данных

Аппаратное обеспечение:
- тома внешней памяти, а также каналы ввода/вывода
- аппаратный процессор и устройства оперативной памяти
Программное обеспечение:
- сис управления данными
- сис управления транзакциями
Однопользовательская система - сис в которой в одно и то же время к базе данных может получить доступ не более одного пользователя
Многопользовательская система - сис в которой в одно и то же время к базе данных может получить доступ несколько пользователей 

#классификация по размещению
1. Банк данных -
	Словарь данных -
2. Распределённая база данных -

#пользователи бд
- конечные пользователи
- разработчики и администраторы приложений
- администраторы и операторы баз данных
- архитекторы баз данных

#Свойства данных
интегрированные - возможность представить данные в нескольких файлах
общие данные -  данные которые могут быть использованы несколькими пользователями

#Структура данных 
объекты - сущности определяющие выделенную часть данных, то о чём нужно хранить инф
связь - способ объединения сущностей 


#презентация 2
Модель данных - формальная теория представления и обработки данных в системе управления базами данных

#модель_данных
По Кодду и Дейту
1. аспект структуры
2. аспект манипуляции
3. аспект целостности


#назначение_модели_данных
в какой-то фотке

#основные_типы_моделей
1. системы оперативной обработки
	1. теоретико-графовые
		- иерархическая модель
		- сетевая модель
	2. теоретико-множественные
		-  что-то в фотке  
		-  что-то в фотке  
2.  что-то в фотке  
#иерарчическая_модель
...

![](https://lh3.googleusercontent.com/proxy/7iOQX0_HvB39BoUpIkwB_cahvnXqWNwd-xO7wObrNfqz-DhGaprCM4qNvt3S-1laJxFewuT67fThu9h8vkmFsD5A)


#Сетевая_модель
...

![](https://studfile.net/html/2706/816/html_ETUwU3B8NT.Relw/img-HLE93C.png)

#Реляционная_модель
...

![](data:image/png;base64,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)

#Постреляционная_модель
...

![](https://studfile.net/html/6674/939/html_h0KyVWQ8Yc.pFfo/img-Cmdc6D.png)

#многомерная_модель
...

![](https://intuit.ru/EDI/20_07_20_2/1595197216-9970/tutorial/632/objects/9/files/07_01_1.jpg)

# 22.01
# Реляционная моель

## термины
- кортеж - набор данных описывающий св-ва одного объекта
- отношение - в реляционной модели физическое представление сущности
- домен - базовый тип данных + описание ограничений
- атрибут - св-во объекта предметной области 
- сущность - класс объектов данных
- тип данных - допустимый стандарт или определённый пользователем задания данных

Физическое представление представляет собой двумерный массив
- запись - строка таблицы
- поле - столбец таблицы 

## ключи
- ключ -поле или группа полей однозначно определяющее запись
- первичный ключ - ключ принятый в качестве основного
- составной ключ - ключ состоящий из нескольких полей
- суррогатный ключ - искусственный ключ добавленный в таблицу для замены составного ключ
- внешний ключ - неключевое поле связанное с ключевым полем другой таблицы

## св-ва отношений
- отсутствие кортежей-дубликатоы
- отсутствие упорядочности атрибутов 
- атморность значений атрибутов
- отсутствие упорядочности кортежей


Правила Кодда (их 13 но почему-то говорят 12

- **Правило 0: Основное правило** (_Foundation Rule_):

	Система, которая рекламируется или позиционируется как РСУБД, должна быть способной управлять базами данных, используя исключительно свои реляционные возможности.

- **Правило 1: Информационное правило** (_The Information Rule_):

	Вся информация в реляционной базе данных на логическом уровне должна быть явно представлена единственным способом: значениями в [таблицах](https://ru.wikipedia.org/wiki/%D0%A2%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B1%D0%B0%D0%B7%D0%B0_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) "Таблица (база данных)").
	данные должны быть атомарными

- **Правило 2: Гарантированный доступ к данным** (_Guaranteed Access Rule_):

	В [реляционной базе данных](https://ru.wikipedia.org/wiki/%D0%A0%D0%B5%D0%BB%D1%8F%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F_%D0%B1%D0%B0%D0%B7%D0%B0_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85 "Реляционная база данных") каждое отдельное (атомарное) значение данных должно быть логически доступно с помощью комбинации имени таблицы, имени столбца и значения [первичного ключа](https://ru.wikipedia.org/wiki/%D0%9F%D0%B5%D1%80%D0%B2%D0%B8%D1%87%D0%BD%D1%8B%D0%B9_%D0%BA%D0%BB%D1%8E%D1%87 "Первичный ключ").

- **Правило 3: Систематическая поддержка отсутствующих значений** (_Systematic Treatment of Null Values_):

	Неизвестные, или отсутствующие значения [NULL](https://ru.wikipedia.org/wiki/NULL_(SQL) "NULL (SQL)"), отличные от любого известного значения, должны поддерживаться для всех [типов данных](https://ru.wikipedia.org/wiki/%D0%A2%D0%B8%D0%BF_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85 "Тип данных") при выполнении любых операций. Например, для числовых данных неизвестные значения не должны рассматриваться как нули, а для символьных данных — как пустые строки.

- **Правило 4: Доступ к словарю данных в терминах реляционной модели** (_Active On-Line Catalog Based on the Relational Model_):

	[Словарь данных](https://ru.wikipedia.org/wiki/%D0%A1%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D1%8C_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85 "Словарь данных") должен сохраняться в форме реляционных таблиц, и СУБД должна поддерживать доступ к нему при помощи стандартных языковых средств, тех же самых, которые используются для работы с реляционными таблицами, содержащими пользовательские данные.

- **Правило 5: Полнота подмножества языка** (_Comprehensive Data Sublanguage Rule_):

	Система управления реляционными базами данных должна поддерживать хотя бы один реляционный язык, который

	- (а) имеет [линейный синтаксис](https://ru.wikipedia.org/w/index.php?title=%D0%9B%D0%B8%D0%BD%D0%B5%D0%B9%D0%BD%D1%8B%D0%B9_%D1%81%D0%B8%D0%BD%D1%82%D0%B0%D0%BA%D1%81%D0%B8%D1%81&action=edit&redlink=1 "Линейный синтаксис (страница отсутствует)"),

	- (б) может использоваться как [интерактивно](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D1%81%D1%82%D1%8C "Интерактивность"), так и в прикладных программах,

	- (в) поддерживает операции определения данных, определения представлений, манипулирования данными ([интерактивные](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D1%81%D1%82%D1%8C "Интерактивность") и программные), ограничители целостности, управления доступом и операции управления [транзакциями](https://ru.wikipedia.org/wiki/%D0%A2%D1%80%D0%B0%D0%BD%D0%B7%D0%B0%D0%BA%D1%86%D0%B8%D1%8F_(%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0) "Транзакция (информатика)") (begin, [commit](https://ru.wikipedia.org/wiki/Commit_(SQL) "Commit (SQL)") и [rollback](https://ru.wikipedia.org/wiki/Rollback "Rollback")).

- **Правило 6: Возможность изменения представлений** (_View Updating Rule_):

	Каждое [представление](https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_(%D0%B1%D0%B0%D0%B7%D1%8B_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) "Представление (базы данных)") должно поддерживать все операции манипулирования данными, которые поддерживают реляционные таблицы: операции выборки, вставки, изменения и удаления данных.

- **Правило 7: Наличие высокоуровневых операций управления данными** (_High-Level Insert, Update, and Delete_):

	Операции вставки, изменения и удаления данных должны поддерживаться не только по отношению к одной строке реляционной таблицы, но и по отношению к любому множеству строк.

- **Правило 8: Физическая независимость данных** (_Physical Data Independence_):

	Приложения не должны зависеть от используемых способов хранения данных на носителях, от [аппаратного обеспечения](https://ru.wikipedia.org/wiki/%D0%90%D0%BF%D0%BF%D0%B0%D1%80%D0%B0%D1%82%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5 "Аппаратное обеспечение") компьютеров, на которых находится реляционная база данных.

- **Правило 9: Логическая независимость данных** (_Logical Data Independence_):

	Представление данных в приложении не должно зависеть от структуры реляционных таблиц. Если в процессе [нормализации](https://ru.wikipedia.org/wiki/%D0%9D%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%84%D0%BE%D1%80%D0%BC%D0%B0 "Нормальная форма") одна реляционная таблица разделяется на две, представление должно обеспечить объединение этих данных, чтобы изменение структуры реляционных таблиц не сказывалось на работе приложений.

- **Правило 10: Независимость контроля целостности** (_Integrity Independence_):

	Вся информация, необходимая для поддержания целостности, должна находиться в словаре данных. Язык для работы с данными должен выполнять проверку входных данных и автоматически поддерживать целостность данных.

- **Правило 11: Независимость от расположения** (_Distribution Independence_):

	База данных может быть распределённой, может находиться на нескольких компьютерах, и это не должно оказывать влияния на приложения. Перенос базы данных на другой компьютер не должен оказывать влияния на приложения.

- **Правило 12: Согласование языковых уровней** (_The Nonsubversion Rule_):

	Если используется низкоуровневый язык доступа к данным, он не должен игнорировать правила безопасности и правила целостности, которые поддерживаются языком более высокого уровня.


# 24.01 
## инструмент 
[draw.io](draw.io) - для создания схем
microsoft visio (визио)
	1. концептуальная модель (с помощью нотации Чена)
	2. инфологическая модель (с помощью нотации Варкера)
	3. даталогическая модель (с помощью расширенной нотации Варкера)
это всё ER (Entity Relation)

# Название работы:  __база данных учёта успеваемости студентов колледжа__ 
 сделать 
	1. концептуальная модель (с помощью нотации Чена)
	2. инфологическая модель (с помощью нотации Варкера)
	3. даталогическая модель (с помощью расширенной нотации Варкера)

ромбик это связь сущностей 
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-24_12-31-33.jpg?raw=true)

# 29.01
# Основы реляционной алгебры

#Реляционная алгебра -замкнутая система операций над отношениями в реляционной модели данных
#замкнутость - это набор таких операций на отношениями что результат каждой операции также является отношением 

## Операции реляционной алгебры Кодда
### базовые 
- объединение отношений
- пересечение отношений
- вычитание отношений
- прямое произведений отношений

### специальные 
...

- операции могут производиться над одним или двумя отношениями
- при выполнении бинарных операций отношения должны быть совместимы по структуре 
- некоторые отношения формально не соместимы ....

## Математический смысл операций
n-арную операцию f можно представить функцией возвращающей отношение и имеющей n отношений в качестве аргументов:

| R=f(R1, R2<...Rn) |
| ---- |
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-28-44.jpg?raw=true)


объединение
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-30-51.jpg?raw=true)


Пересечение отношений
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-34-25.jpg?raw=true)


Вычитание 
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-36-25.jpg?raw=true)


Прямое произведение
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-38-40.jpg?raw=true)


Ограничение отношения (выборка)
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-44-04.jpg?raw=true)


Проекция отношения
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-45-22.jpg?raw=true)


Деление отношений
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-46-23.jpg?raw=true)


![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-51-55.jpg?raw=true)



![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_10-54-09.jpg?raw=true)

![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-01-29_11-02-26.jpg?raw=true)


![]()







#объектно-реляционная_модель
...

в картинке на гитхабе

# 12.02
# Case - средства 
---
### Основные понятия

__Case  разработка ПО с помощью компьютера - автоматизации разработки ИС
Case средства - программные средства поддерживающие процессы создания и/или сопровождения ИС такие как анализ и формулировка требований проектирования БД и приложений, генерация кода, тестирование, обеспечение качества, управление конфигурацией и проектом
Case система - набор case средств имеющих определённое функциональное предназначение и выполненных в рамках единого программного продукта
Case технология - совокупность методологий анализа, проектирования, разработки и сопровождения сложных систем__

Причины появления технологии
- подготовка аналитиков и программистов - специалистов модульного и структурного программирования
- широкое внедрение и постоянный рост производительности компьютеров, позволившие использовать эффективные графические средства и автоматизировать большинство этапов проектирования
- внедрение сетевой технологии, предоставившей возможность объединять усилия отдельных исполнителей в единый процесс проектирования

### RTE (round trip engineering) - возвратное проектирование
- проектирование прототипа модели
- разработка прототипа
- доработка исходной модели 
- разработка на основе доработанной модели

### Engineering
- прямое проектирование (forward engineering)
- обратное проектирование (reverse -engineering)
построение ER-моделей
Case ср-ва поддерживают оба процесса

#### характерные особенности Case средств
-  Мощные графические средства для описания и документирования ИС, обеспечивающие удобный интерфейс с разработчиком
- Использование специальным образом организованного хранилища проектных метаданных (репозитория)
- Интеграция отдельных компонент CASE-средств, обеспечивающая управляемость процессом разработки ИС
- Поддержка коллективной разработки и управления проектом
- Макетирование (прототипирование)

### классификация case средств
- по ориентации на этапы жизненного цикла
- по функциональной полноте 
- по типу используемой модели
- по степени независимости от СУБД

### Классификация по ориентации на этапы жизненного цикла
- Средства анализа, предназначенные для построения и анализа моделей предметной области
- Средства анализа и проектирования, обеспечивающие создание проектных спецификаций
- Средства проектирования БД. обеспечивающие моделирование данных и разработку схем БД для основных СУБД
- Средства разработки приложений

### Классификация по функциональной полноте

- ﻿﻿Системы, предназначенные для решения частных задач - на одном и/или нескольких этапах жизненного цикла
- Интегрированные системы, поддерживающие весь жизненный цикл ИС и связанные с общим репозиторием
### Классификация по типу используемых моделей
- Структурные  
- Объектно-ориентированные
- ﻿﻿Комбинированные

### Классификация по степени независимости от СУБД
Независимые системы - поставляются в виде автономных систем, не входящих в состав конкретной СУБД

- Встроенные в СУБД - обычно поддерживают формат данных
- СУБД, в состав которой они входят (возможна поддержка и других форматов баз данных)
### Примеры
- Allfusion erwin data modeler
- Power designer компании Sybase
- Пакет Design/IDEF (META Soft Corp.)
- Designer oracle
---
---

# СУБД
![](https://github.com/rafvvv/-_-/blob/main/photo/photo_2024-02-12_11-05-43.jpg?raw=true)

### Классификация ИС по типу СУБД

- ﻿﻿Локальные
- ﻿﻿Удаленные  
    - Файл-серверные  
    - Клиент-серверные (двухуровневые и трехуровневые)  
    - Распределенные

__Недостатки файл-серверной архитектуры__
- Большой объём сетевого трафика
- ﻿﻿Сложность реализации параллельности, восстановления, безопасности и целостности
Пример: Access
 
 __Преимущества клиент-серверной архитектуры__
- ﻿﻿Обеспечение более широкого доступа к существующим БД
- ﻿﻿Повышение производительности системы
- ﻿﻿Снижение стоимости аппаратного обеспечения
- ﻿﻿Сокращение коммуникационных расходов
- ﻿﻿Повышение уровня непротиворечивости данных
- ﻿﻿Данная архитектура согласуется с архитектурой открытых систем и может быть использована для организации средств работы с распределенными системами

### Трёхуровневая архитектура

Достоинства
- ﻿﻿Широкие возможности масштабирования
- ﻿﻿Высокая безопасность и надежность
Недостатки:
- ﻿﻿Повышенная сложность создания
- ﻿﻿Повышенная сложность администрирования
### Основные функции СУБД

- ﻿﻿Управление данными во внешней памяти
- ﻿﻿Управление данными в оперативной памяти
- ﻿﻿Управление транзакциями
- С Обеспечение надежности
- Поддержка языков БД (сейчас это SQL)

### Управление данными во внешней памяти
- ﻿﻿Сохранять, извлекать и обновлять данные в базе данных
- ﻿﻿Контролировать доступ к данным
- ﻿﻿Обеспечивать параллельную работу нескольких пользователей
- ﻿﻿Поддерживать целостность данных
Блокировка - меры, не допускающие изменение данных пользователем во время работы другого пользователя
Целостность - свойство базы данных содержать полную, непротиворечивую и адекватно отражающую предметную область информацию

### Управление данными в оперативной памяти
-  Буферизация работы с БД
- Поддержка собственного набора буферов и операций над ними
### Контроль транзакций
Транзакция - совокупность операций над БД, рассматриваемая как единое целое. Действия должны быть выполнены все или ни одного.
Это средство защиты логической целостности
- Обнаружение конфликтов
- Откат транзакций
### Обеспечение надёжности
Это средства защиты физической целостности
Надёжность - СУБД должна иметь возможность восстановить последнее согласованное состояние БД после любого аппаратного или программного сбоя
- Журнализация изменений
- Резервное копирование
- Восстановление

### Вспомогательные функции СУБД
- ﻿﻿Экспорт/импорт данных
- ﻿﻿Мониторинг базы данных
- ﻿﻿Статистический анализ производительности
- ﻿﻿Реорганизация индексов
- ﻿﻿«Сборка» мусора

### Структура СУБД

- ﻿﻿Ядро СУБД  
- Процессор языка базы данных
- ﻿﻿Подсистема поддержки времени выполнения
- ﻿﻿Утилиты, обеспечивающие дополнительные возможности
