# $roleExists
desc
### Использование
```php
$roleExists[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$roleExists',
  code: `
$roleExists[roleId;сервер?]`
// Возвращает: ...
})
```
