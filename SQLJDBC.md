##### [job4j_interviews](https://github.com/shaporen/job4j_interviews/blob/main/README.md)
#### Оглавление
+ [1. Что такое SQL?](#1-Что-такое-SQL)
+ [2. Что такое DML и DDL?](#2-Что-такое-DML-и-DDL)
+ [3. Что такое первичный ключ?](#3-Что-такое-первичный-ключ)
+ [4. Что такое внешний ключ?](#4-Что-такое-внешний-ключ)
+ [5. Какие виды связей между таблицами существуют и как они организуются?](#5-Какие-виды-связей-между-таблицами-существуют-и-как-они-организуются)
+ [6. Опишите как вставить, удалить, обновить данные в(из) таблицу(ы).](#6-Опишите-как-вставить-удалить-обновить-данные-виз-таблицуы)
+ [7. Что такое нормализация БД?](#7-Что-такое-нормализация-БД)
+ [8. Что такое денормализация БД? Для чего она нужна?](#8-Что-такое-денормализация-БД-Для-чего-она-нужна)
+ [9. Что такое кластерный и некластерный индексы?](#9-Что-такое-кластерный-и-некластерный-индексы)
+ [10. Какие типы соединений (join) таблиц существуют? В чем их разница?](#10-Какие-типы-соединений-join-таблиц-существуют-В-чем-их-разница)
+ [11. Что такое SQL курсор?](#11-Что-такое-SQL-курсор)
+ [12. Опишите шаги по созданию и использованию курсора.](#12-Опишите-шаги-по-созданию-и-использованию-курсора)
+ [13. Что такое транзакция?](#13-Что-такое-транзакция)
+ [14. Что такое триггер? Какие типы триггеров Вы знаете?](#14-Что-такое-триггер-Какие-типы-триггеров-Вы-знаете)
+ [15. В чем разница между where и having?](#15-В-чем-разница-между-where-и-having)
+ [16. Что такое подзапрос (sub-query)?](#16-Что-такое-подзапрос-sub-query)
+ [17. Что такое union?](#17-Что-такое-union)
+ [18. Что такое group by?](#18-Что-такое-group-by)
+ [19. Что такое хранимые процедуры?](#19-Что-такое-хранимые-процедуры)
+ [20. Что такое view (представление)?](#20-Что-такое-view-представление)
+ [21. Что такое JDBC?](#21-Что-такое-JDBC)
+ [22. Что нужно для работы с той или иной БД?](#22-Что-нужно-для-работы-с-той-или-иной-БД)
+ [23. Как зарегистрировать драйвер?](#23-Как-зарегистрировать-драйвер)
+ [24. Как получить Connection?](#24-Как-получить-Connection)
+ [25. Что такое Statement, PreparedStatement? В чем разница между ними?](#25-Что-такое-Statement-PreparedStatement-В-чем-разница-между-ними)
+ [26. Что такое ResultSet?](#26-Что-такое-ResultSet)
+ [27. В чем разница между методами execute, executeUpdate, executeQuery?](#27-В-чем-разница-между-методами-execute-executeUpdate-executeQuery)
+ [28. Можно ли использовать возвращаемое значение execute() для проверки, что что-то обновилось?](#28-Можно-ли-использовать-возвращаемое-значение-execute-для-проверки-что-что-то-обновилось)
+ [29. Как получить при вставке сгенерированные ключи? Как это сделать на чистом SQL?](#29-Как-получить-при-вставке-сгенерированные-ключи-Как-это-сделать-на-чистом-SQL)
+ [30. Для чего используется конструкция try-with-resources?](#30-Для-чего-используется-конструкция-try-with-resources)



#### 1. Что такое SQL?
[_к оглавлению_](#Оглавление)
#### 2. Что такое DML и DDL?
[_к оглавлению_](#Оглавление)
#### 3. Что такое первичный ключ?
[_к оглавлению_](#Оглавление)
#### 4. Что такое внешний ключ?
[_к оглавлению_](#Оглавление)
#### 5. Какие виды связей между таблицами существуют и как они организуются?
[_к оглавлению_](#Оглавление)
#### 6. Опишите как вставить, удалить, обновить данные в(из) таблицу(ы).
[_к оглавлению_](#Оглавление)
#### 7. Что такое нормализация БД?
[_к оглавлению_](#Оглавление)
#### 8. Что такое денормализация БД? Для чего она нужна?
[_к оглавлению_](#Оглавление)
#### 9. Что такое кластерный и некластерный индексы?
[_к оглавлению_](#Оглавление)
#### 10. Какие типы соединений (join) таблиц существуют? В чем их разница?
[_к оглавлению_](#Оглавление)
#### 11. Что такое SQL курсор?
[_к оглавлению_](#Оглавление)
#### 12. Опишите шаги по созданию и использованию курсора.
[_к оглавлению_](#Оглавление)
#### 13. Что такое транзакция?
[_к оглавлению_](#Оглавление)
#### 14. Что такое триггер? Какие типы триггеров Вы знаете?
[_к оглавлению_](#Оглавление)
#### 15. В чем разница между where и having?
[_к оглавлению_](#Оглавление)
#### 16. Что такое подзапрос (sub-query)?
[_к оглавлению_](#Оглавление)
#### 17. Что такое union?
[_к оглавлению_](#Оглавление)
#### 18. Что такое group by?
[_к оглавлению_](#Оглавление)
#### 19. Что такое хранимые процедуры?
[_к оглавлению_](#Оглавление)
#### 20. Что такое view (представление)?
[_к оглавлению_](#Оглавление)
#### 21. Что такое JDBC?
[_к оглавлению_](#Оглавление)
#### 22. Что нужно для работы с той или иной БД?
[_к оглавлению_](#Оглавление)
#### 23. Как зарегистрировать драйвер?
[_к оглавлению_](#Оглавление)
#### 24. Как получить Connection?
[_к оглавлению_](#Оглавление)
#### 25. Что такое Statement, PreparedStatement? В чем разница между ними?
[_к оглавлению_](#Оглавление)
#### 26. Что такое ResultSet?
[_к оглавлению_](#Оглавление)
#### 27. В чем разница между методами execute, executeUpdate, executeQuery?
[_к оглавлению_](#Оглавление)
#### 28. Можно ли использовать возвращаемое значение execute() для проверки, что что-то обновилось?
[_к оглавлению_](#Оглавление)
#### 29. Как получить при вставке сгенерированные ключи? Как это сделать на чистом SQL?
[_к оглавлению_](#Оглавление)
#### 30. Для чего используется конструкция try-with-resources?
[_к оглавлению_](#Оглавление)
