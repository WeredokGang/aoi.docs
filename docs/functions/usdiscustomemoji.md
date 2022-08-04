# $isCustomEmoji
desc
### Использование
```php
$isCustomEmoji[emoji;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| emoji |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isCustomEmoji',
  code: `
$isCustomEmoji[emoji;сервер?]`
// Возвращает: ...
})
```
