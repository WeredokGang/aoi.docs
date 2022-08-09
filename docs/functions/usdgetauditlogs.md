# $getAuditLogs
desc
### Использование
```php
$getAuditLogs[limit?;userId?;action?;сервер?;format?;]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| limit |  |  | Нет | 
| userId |  |  | Нет | 
| action |  |  | Нет |
| сервер |  |  | Нет |
| format |  |  | Нет |
|  |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$getAuditLogs',
  code: `
$getAuditLogs[limit?;userId?;action?;сервер?;format?;]`
// Возвращает: ...
})
```
