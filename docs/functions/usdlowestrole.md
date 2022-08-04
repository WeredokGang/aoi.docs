# $lowestRole
desc
### Использование
```php
$lowestRole[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$lowestRole',
  code: `
$lowestRole[userId?;сервер?]`
// Возвращает: ...
})
```
