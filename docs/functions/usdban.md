# $ban
Блокирует указанного пользователя на сервере и очищает сообщения за указанный период времени. Не может заблокировать пользователя по айпи / устройству из-за ограничений Discord Api.
### Использование
```php
$ban[сервер?;пользователь;дни?;причина]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер | айди сервера где нужно заблокировать пользователя | айди | Нет | 
| пользователь | айди пользователя которого нужно заблокировать | айди | Да | 
| дни | дни, за которые будет очищена история сообщений от пользователя | число | Нет |
| причина | отображаемая в журнале аудита причина блокировка | текст | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$ban',
  code: `
$ban[$guildID;$mentioned[1;no];120;Модератор $username заблокировал этого пользователя]


`
})
```
