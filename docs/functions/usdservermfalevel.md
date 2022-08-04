# $serverMFALevel
desc
### Использование
```php
$serverMFALevel[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverMFALevel',
  code: `
$serverMFALevel[сервер?]`
// Возвращает: ...
})
```
