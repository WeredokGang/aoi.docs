# $serverFeatures
desc
### Использование
```php
$serverFeatures[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverFeatures',
  code: `
$serverFeatures[сервер?]`
// Возвращает: ...
})
```
