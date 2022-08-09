# $serverRulesChannelID
desc
### Использование
```php
$serverRulesChannelID[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverRulesChannelID',
  code: `
$serverRulesChannelID[сервер?]`
// Возвращает: ...
})
```
