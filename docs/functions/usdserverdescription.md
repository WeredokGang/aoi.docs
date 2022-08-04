# $serverDescription
desc
### Использование
```php
$serverDescription[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverDescription',
  code: `
$serverDescription[сервер?]`
// Возвращает: ...
})
```
