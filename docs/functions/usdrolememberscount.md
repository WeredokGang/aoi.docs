# $roleMembersCount
desc
### Использование
```php
$roleMembersCount[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$roleMembersCount',
  code: `
$roleMembersCount[roleId;сервер?]`
// Возвращает: ...
})
```
