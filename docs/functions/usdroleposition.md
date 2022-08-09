# $rolePosition
desc
### Использование
```php
$rolePosition[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$rolePosition',
  code: `
$rolePosition[roleId;сервер?]`
// Возвращает: ...
})
```
