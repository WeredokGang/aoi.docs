# $serverEmojiExists
desc
### Использование
```php
$serverEmojiExists[emoji;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| emoji |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$serverEmojiExists',
  code: `
$serverEmojiExists[emoji;сервер?]`
// Возвращает: ...
})
```
