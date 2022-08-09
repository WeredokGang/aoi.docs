# $pruneMembers
desc
### Использование
```php
$pruneMembers[days?;сервер?;roleIds;dry?;reason;count?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| days |  |  | Нет | 
| сервер |  |  | Нет | 
| roleIds |  |  | Да |
| dry |  |  | Нет |
| reason |  |  | Да |
| count |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$pruneMembers',
  code: `
$pruneMembers[days?;сервер?;roleIds;dry?;reason;count?]`
// Возвращает: ...
})
```
