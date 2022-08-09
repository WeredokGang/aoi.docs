# База данных

В aoi.js есть возможность использовать базу данных. В ней хранятся все данные о временных и постоянных переменных. Вы можете её настраивать как вам угодно: 
```javascript
database: {
  type: "тип",
  db: require("пакет данных.db"),
  tables: ["таблицы"],
  promisify: true или false 
}
```

* `type` - Тип базы данных:
     *  `dbdjs.db` - Стандартный тип базы данных
     *  `dbdts.db` - Для поддержки пакета dbdts.db
     *  `aoi.db` - Для поддержки бета-версии будущей стандартной базы данных aoi.js
     *  `aoi.mongo` - Для поддержки MongoDB
     *  `aoi.fb` - Для поддержки FireBase
     
* `db` - Модуль базы данных:
```javascript
db: require("dbdjs.db")
```
* `tables` - Массив с названиями таблиц баз данных. Они нужны для создания базы данных и её использования. Например, вы можете создать переменную `abc` и таблицы `main` `tweak`. Пропишем следующие функции, для того чтобы понять их суть: 
```javascript
$setUserVar[abc;123;$authorID;main] //Устанавливает значение переменной abc для таблицы main
$setUserVar[abc;456;$authorID;tweak] //Устанавливает значение переменной abc для таблицы tweak
$getUserVar[abc;$authorID;main] //Вернёт 123
$getUserVar[abc;$authorID;tweak] //Вернёт 456
```
* `promisify` - Отправлять ли сообщение о том что база данных работает.

Настройки по-умолчанию:
```javascript
database: {
  type: "dbdjs.db",
  db: require("dbdjs.db"),
  tables: ["main"],
  promisify: true
}
```

###### Функции для переменых по умолчанию используют таблицу main