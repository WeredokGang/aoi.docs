# $reactionCount
desc
### Использование
```php
$reactionCount[канал;messageId;emojiResolver]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| messageId |  |  | Да | 
| emojiResolver |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$reactionCount',
  code: `
$reactionCount[канал;messageId;emojiResolver]`
// Возвращает: ...
})
```
