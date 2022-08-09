# Пользовательские функции

Вы можете создавать собственные функции в aoi.js, используя его же функционал. 

## Пример создания
```javascript
bot.functionManager.createCustomFunction({
  name: "$function",
  type: "тип",
  params: ["массив"],
  code: `функция`
})
```
* Опции этой функции
  * `name` - название функции с $
  * `type` - кодировка, доступные виды кодировки: aoi.js или djs
  * `params` - параметры функции. Все необязательны
  * `code` - код, который будет выполняться при использовании функции

Чтобы получить значение параметра используйте {параметр}

## Примеры
```javascript
bot.functionManager.createCustomFunction({
  name: "$isAdmin",
  type: "aoi.js",
  params: ["id"],
  code: `$hasPerms[$guildID;$if[{id}!=undefined;{id};$authorID];admin]`
})
```
```javascript
bot.functionManager.createCustomFunction({
  name: "$isDeveloper",
  type: "aoi.js",
  params: ["id"],
  code: `$checkContains[$botOwnerID;$if[{id}!=undefined;{id};$authorID]]`
})
```
```javascript
bot.functionManager.createCustomFunction({
  name: "$api",
  type: "djs",
  params: [],
  code: `message.channel.send("https://discord.com/api/v10")`
})
```
})
