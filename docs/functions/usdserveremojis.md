# $serverEmojis
desc
### Использование
```php
$serverEmojis[sep?;";сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| sep |  |  | Нет | 
| " |  |  | Да | 
| сервер |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$serverEmojis',
  code: `
$serverEmojis[sep?;";сервер?]`
// Возвращает: ...
})
```
