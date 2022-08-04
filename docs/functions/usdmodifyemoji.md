# $modifyEmoji
desc
### Использование
```php
$modifyEmoji[сервер;emojiId;name;...roles]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| emojiId |  |  | Да | 
| name |  |  | Да |
| ...roles |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$modifyEmoji',
  code: `
$modifyEmoji[сервер;emojiId;name;...roles]`
// Возвращает: ...
})
```
