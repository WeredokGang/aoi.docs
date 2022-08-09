# $addMessageReactions
Добавляет реакции к указанному сообщению
### Использование
```php
$addMessageReactions[канал;сообщение;...reactions]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| сообщение |  |  | Да | 
| ...reactions |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$addMessageReactions',
  code: `
$addMessageReactions[$channelID;$messageID;:joy:]`
// Возвращает: ...
})
```
