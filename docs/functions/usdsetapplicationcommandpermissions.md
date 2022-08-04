# $setApplicationCommandPermissions
desc
### Использование
```php
$setApplicationCommandPermissions[сервер?;id;...perms]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| id |  |  | Да | 
| ...perms |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$setApplicationCommandPermissions',
  code: `
$setApplicationCommandPermissions[сервер?;id;...perms]`
// Возвращает: ...
})
```
