######  Статья будет постоянно обновляться
# Первая работа с пакетом


В этой статье вы можете увидеть рекомендации по тому как начать писать ботов на этой библиотеки.

## Необходимые знания о библиотеке и о том как она работает
Aoi.js - **Библиотека, написаная на [discord.js](https://github.com/discordjs/discord.js)**, которая имеет свои стандарты для чтения и интерпритации кода:

### Функции
* Название функции может быть только на английском языке. Название может быть написано без заглавных или с заглавными буквами, в этом нету разницы, чтение будет одинаковое. Для удобства везде - в документации, коде а также сообществе принято каждое слово писать с заглавной, чтобы код был читабельным.

```javascript
$function[число;текст;сообщение;перечисление;данные;вложение/путь] 

```

* Обьяснения про каждый тип опции
  * число - любое целое число в пределах от -36028797019е16 до 36028797019e16  
```javascript
123456789
```
  * текст - любой текст с любой расскладки или кодировки
```javascript
любой текст - any text
```
  * сообщение - Расширенная опция для любого текста, которая поддерживает парсинг, JSON / djs объекты для создания сообщения от бота
```javascript
{
  "content": "Привет, мир!"
}
```
  * перечисление - перечисление аргументов используя :
```javascript
Параметр функции 1:Параметр функции 2:Параметр функции 3
```
  * данные - перемеенные в виде Json-объекта 
```javascript
{
  "abc": "Это значение переменной"
}
```
  * вложение/путь - ссылка или путь к изображению или файла для вложения 
```javascript
https://cdn.discordapp.com/attachments/993602810203615323/1001240096982442004/7285a655445f14bd3c368af66035952f_w200.gif
```

* Важные примечания к работе функций:
  * Чтение кода идёт снизу вверх и справа налево
  * Если функции с таким названием не найдено, она выдастся в виде текста
  * Каждая ошибка, где вы не закрыли скобку или неправильно указали опции, может выводится не в чат а в консоль
  * Выключенные функции в опциях клиента будут работать в функции $eval и $djsEval
  * Каждый тип команды имеет логичекие данные, например, сводку про автора, канал, сервер где используется функция. Таким образом, у типа join есть автор, который присоеденился и сервер к которому он присоеденился, а у обратного вызова ready нету ничего.
  * Если функция ничего не выдаёт, и эта функция не связана с запросами в веб-ресурсах (кроме Discord Api), она выдаст пустоту: `$if[$role[$roleid[Admin];asdfghjkl]==;Пустота;Не пустота]`
  * Функция $wait сбрасывает таймер после выключения или перезапуска сервера с клиентом, поэтому надёжнее использовать таймеры с функцией $setTimeout - они не сбрасываются в любом случае
  * Функции, которые создают слэш команды или их редактируют - выполняются сразу, если у вас она не создалась или не отредактировалась - попробуйте перезапустить Discord
  * Для использования некоторых функций нужны определенные интенты или обратные вызовы
### Обратные вызовы
* Обратные вызовы делятся на несколько подвидов:
  * Разрешающие использование опрёделенных функций и типов команд (такие как onInteractionCreate)
  * Разрешающие использовать свой тип команд (такие как onUserUpdate)
  * Разрешающие использовать определенные функции (например $status - onUserpPresenceUpdate)

Их можно использовать в различных целях: Система логирования, отслеживание статусов пользователей, авто-модерирование сервера, защита от рейдов, защита от опасных ботов, система розыгрышей, система напоминаний, уведомлений о изменениях бота, выполнение одного и того же кода много раз / на всех серверах или каналах
 Важно помнить о том, что существуют лимиты Discord и Discord API - Вы не можете сделать массовую рассылку сообщения для большого количества пользователей, иначе Discord может принять меры: от сброса токена за слишком частые запросы до временной блокировки клиента бота. Так-же для кодов и систем которые испольуют loop, ready и awaited типы команд стоит помнить о лимитах хостинга - оперативная память не бесконечна
