# $handleError
Возвращает информацию о ошибке из обратного вызова fuctionError
### Использование
```php
$handleError[опция]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| опция | опция того, что вернёт функция | текст | Да |  

### Доступные опции
* `error` - Возвращает текст ошибки
* `command` - Возвращает название команды с ошибкой
* `function` - Возвращает название функции с ошибкой
## Пример(ы)

```javascript
bot.functionErrorcommand({
  name: 'functionError',
  code: `$channelSendMessage[1001177000460963951;{newEmbed:{title:Произошла ошибка!}{field:Команда:$handleError[command]:yes}{field:Функция:$handleError[function]:yes}{field:Ошибка:$handleError[error]:yes}{color:ff0000}};no]
`
})
```