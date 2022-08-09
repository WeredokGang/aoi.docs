# $serverAvailable
desc
### Использование
```php
$serverAvailable[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverAvailable',
  code: `
$serverAvailable[сервер?]`
// Возвращает: ...
})
```
