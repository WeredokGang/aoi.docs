# $defaultMessageNotification
desc
### Использование
```php
$defaultMessageNotification[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$defaultMessageNotification',
  code: `
$defaultMessageNotification[сервер?]`
// Возвращает: ...
})
```
