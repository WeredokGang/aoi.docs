# $reactionCount
desc
### Использование
```php
$reactionCount[канал;сообщение;emojiResolver]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| сообщение |  |  | Да | 
| emojiResolver |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$reactionCount',
  code: `
$reactionCount[канал;сообщение;emojiResolver]`
// Возвращает: ...
})
```
