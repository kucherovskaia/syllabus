# Курс Базы данных
### весенний семестр 2015 года, СПбГУАП, кафедра 44

[Требования к экзамену](https://github.com/db2015ss/syllabus/blob/master/exam/exam.md)

[Быстрые вопросы](https://github.com/db2015ss/syllabus/blob/master/exam/fast.md)

[Теоретические вопросы](https://github.com/db2015ss/syllabus/blob/master/exam/theory.md)

[Дополнительные вопросы](https://github.com/db2015ss/syllabus/blob/master/exam/practice.md)

__Важно__

Если у вас есть какие-то вопросы, можно задавать их, создавая issue к этому репозиторию. Как создавать issue, [описано в указаниях по регистрации в организации](https://github.com/db2015ss/students). Также можно отвечать на вопросы однокурсников, заданные в виде issue, а также уведомлять преподавателя об ошибках или неточностях в системе приема/сдачи лабораторных работ (эта схема экспериментальна и применяется впервые). И то, и другое будет расценено как помощь в организации курса и учтено при аттестации.

-----

## Содержание теоретического курса

* Введение в реляционные базы данных
* Реляционная алгебра
* Теория нормализации
* SQL
* Обработка транзакций

-----

## Содержание лабораторного курса

Лабораторный курс по дисциплине включает 6 лабораторных работ.

__Важно__

Для лабораторных работ 3-5 предусмотрена сдача в онлайн-формате на сайте GitHub. Инструкции [здесь](https://github.com/db2015ss/syllabus/blob/master/git.md).

1. [Инфологическое моделирование предметной области](https://github.com/db2015ss/syllabus/blob/master/labworks/labwork1.md)
* [Создание базы данных в СУБД Microsoft Access](https://github.com/db2015ss/syllabus/blob/master/labworks/labwork2.md)
* [Создание базы данных в СУБД SQLite](https://github.com/db2015ss/syllabus/blob/master/labworks/labwork3.md) ([репозиторий](https://github.com/db2015ss/labwork3))
* [Создание представлений на основании запросов на выборку в СУБД SQLite. Запросы на модификацию и удаление данных в СУБД SQLite](https://github.com/db2015ss/syllabus/blob/master/labworks/labwork4.md) ([репозиторий](https://github.com/db2015ss/labwork4))
* [Создание триггеров в СУБД SQLite](https://github.com/db2015ss/syllabus/blob/master/labworks/labwork5.md) ([репозиторий](https://github.com/db2015ss/labwork5))
* [Управление транзакциями в СУБД MySQL](https://github.com/db2015ss/syllabus/blob/master/labworks/labwork6.md)

-----

## Содержание практического курса

Практический курс по дисциплине включает 4 контрольных работы.

1. [Реляционная алгебра](https://github.com/db2015ss/syllabus/blob/master/tests/test1.md)
* [Теория нормализации](https://github.com/db2015ss/syllabus/blob/master/tests/test2.md) ([результаты](https://github.com/db2015ss/syllabus/blob/master/tests/test2res.md))
* [SQL](https://github.com/db2015ss/syllabus/blob/master/tests/test3.md)
* <s>Индексы</s>

-----

## Примерный график изучения дисциплины

|     Период    |       Материал лекций       |   Выполняемая ЛР  |      Выполняемая КР     |
|:-------------:|:---------------------------:|:-----------------:|:-----------------------:|
| конец февраля | реляционная модель, алгебра | 1 (моделирование) |                         |
| начало марта  | теория нормализации         |                   | 1 (реляционная алгебра) |
| конец марта   | SQL DML                     | 2 (Access)        | 2 (теория нормализации) |
| начало апреля | SQL SELECT                  | 3 (SQL DML)       |                         |
| конец апреля  | SQL триггеры                | 4 (SQL SELECT)    | 3 (SQL)                 |
| начало мая    | индексы                     | 5 (SQL триггеры)  |                         |
| конец мая     | транзакции                  | 6 (транзакции)    | 4 (индексы)             |