# $memberJoinedDate
desc
### Использование
```php
$memberJoinedDate[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$memberJoinedDate',
  code: `
$memberJoinedDate[userId?;сервер?]`
// Возвращает: ...
})
```
