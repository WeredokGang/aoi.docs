# functionError
Выполняет код, когда бот выводит ошибку от класса AoiError. Для получения информации о ошибке используйте функцию [$handleError](functions/usdhandleerror.md)

### Использование
```php
bot.functionErrorCommand({
channel: "",
code: ``
})
```
## Пример(ы)

```javascript
bot.functionErrorcommand({
  name: 'functionError',
  code: `$channelSendMessage[1001177000460963951;{newEmbed:{title:Произошла ошибка!}{field:Команда:$handleError[command]:yes}{field:Функция:$handleError[function]:yes}{field:Ошибка:$handleError[error]:yes}{color:ff0000}};no]
`
})
```