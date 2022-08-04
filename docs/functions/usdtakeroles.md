# $takeRoles
desc
### Использование
```php
$takeRoles[сервер;userId;...roleId]
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
  name: '$takeRoles',
  code: `
$takeRoles[сервер;userId;...roleId]`
// Возвращает: ...
})
```
