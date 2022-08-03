# $channelSendMessage
desc
### Использование
```php
$channelSendMessage[channelId;message;returnId?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| channelId |  |  | Да | 
| message |  |  | Да | 
| returnId |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$channelSendMessage',
  code: `
$channelSendMessage[channelId;message;returnId?]`
// Возвращает: ...
})
```