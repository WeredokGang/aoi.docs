# $takeRole
desc
### Использование
```php
$takeRole[сервер;userId;roleId]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| userId |  |  | Да | 
| roleId |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$takeRole',
  code: `
$takeRole[сервер;userId;roleId]`
// Возвращает: ...
})
```
