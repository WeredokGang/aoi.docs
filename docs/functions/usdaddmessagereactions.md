# $addMessageReactions
Добавляет реакции к указанному сообщению
### Использование
```php
$addMessageReactions[канал;messageId;...reactions]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| messageId |  |  | Да | 
| ...reactions |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$addMessageReactions',
  code: `
$addMessageReactions[$channelID;$messageId;:joy:]`
// Возвращает: ...
})
```
