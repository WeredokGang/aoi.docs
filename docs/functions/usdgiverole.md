# $giveRole
desc
### Использование
```php
$giveRole[сервер;userId;roleId]
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
  name: '$giveRole',
  code: `
$giveRole[сервер;userId;roleId]`
// Возвращает: ...
})
```
