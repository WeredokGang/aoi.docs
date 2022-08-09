# $setRolePosition
desc
### Использование
```php
$setRolePosition[roleId;newPosition;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| newPosition |  |  | Да | 
| сервер |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$setRolePosition',
  code: `
$setRolePosition[roleId;newPosition;сервер?]`
// Возвращает: ...
})
```
