# $roleName
desc
### Использование
```php
$roleName[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$roleName',
  code: `
$roleName[roleId;сервер?]`
// Возвращает: ...
})
```
