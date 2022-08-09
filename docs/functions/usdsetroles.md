# $setRoles
desc
### Использование
```php
$setRoles[сервер;memberId;...roleIds]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| memberId |  |  | Да | 
| ...roleIds |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$setRoles',
  code: `
$setRoles[сервер;memberId;...roleIds]`
// Возвращает: ...
})
```
