# $giveRoles
desc
### Использование
```php
$giveRoles[сервер;userId;...roleId]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| userId |  |  | Да | 
| ...roleId |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$giveRoles',
  code: `
$giveRoles[сервер;userId;...roleId]`
// Возвращает: ...
})
```
