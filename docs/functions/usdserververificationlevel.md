# $serverVerificationLevel
desc
### Использование
```php
$serverVerificationLevel[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverVerificationLevel',
  code: `
$serverVerificationLevel[сервер?]`
// Возвращает: ...
})
```
