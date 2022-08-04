# $forEachRole
desc
### Использование
```php
$forEachRole[сервер?;time?;awaitData;...cmds]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| time |  |  | Нет | 
| awaitData |  |  | Да |
| ...cmds |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$forEachRole',
  code: `
$forEachRole[сервер?;time?;awaitData;...cmds]`
// Возвращает: ...
})
```
