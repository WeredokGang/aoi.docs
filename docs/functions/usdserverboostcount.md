# $serverBoostCount
desc
### Использование
```php
$serverBoostCount[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverBoostCount',
  code: `
$serverBoostCount[сервер?]`
// Возвращает: ...
})
```
