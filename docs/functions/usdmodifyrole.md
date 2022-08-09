# $modifyRole
desc
### Использование
```php
$modifyRole[сервер;roleId;...roleDatas]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| roleId |  |  | Да | 
| ...roleDatas |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$modifyRole',
  code: `
$modifyRole[сервер;roleId;...roleDatas]`
// Возвращает: ...
})
```
