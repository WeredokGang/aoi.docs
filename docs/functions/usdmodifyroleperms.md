# $modifyRolePerms
desc
### Использование
```php
$modifyRolePerms[сервер;roleId;...perms]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| roleId |  |  | Да | 
| ...perms |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$modifyRolePerms',
  code: `
$modifyRolePerms[сервер;roleId;...perms]`
// Возвращает: ...
})
```
