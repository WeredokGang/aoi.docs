# $rolePerms
desc
### Использование
```php
$rolePerms[roleId;sep?;';сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| sep |  |  | Нет | 
| ' |  |  | Да |
| сервер |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$rolePerms',
  code: `
$rolePerms[roleId;sep?;';сервер?]`
// Возвращает: ...
})
```
