# $serverBoostLevel
desc
### Использование
```php
$serverBoostLevel[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverBoostLevel',
  code: `
$serverBoostLevel[сервер?]`
// Возвращает: ...
})
```
