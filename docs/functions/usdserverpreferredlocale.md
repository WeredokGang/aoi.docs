# $serverPreferredLocale
desc
### Использование
```php
$serverPreferredLocale[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverPreferredLocale',
  code: `
$serverPreferredLocale[сервер?]`
// Возвращает: ...
})
```
