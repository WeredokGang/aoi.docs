# $defaultMessageNotification
Устанавливает настройки уведомлений по умолчанию на указанном сервере
### Использование
```php
$defaultMessageNotification[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер | сервер, на котором нужно сбросить настройки уведомлений | айди | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$defaultMessageNotification',
  code: `
$defaultMessageNotification`
// Возвращает: 
})
```
