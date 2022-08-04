# $unPinMessage
desc
### Использование
```php
$unPinMessage[сообщение?;channelId?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сообщение |  |  | Нет | 
| channelId |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$unPinMessage',
  code: `
$unPinMessage[сообщение?;channelId?]`
// Возвращает: ...
})
```
