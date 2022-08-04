# $deleteRoles
desc
### Использование
```php
$deleteRoles[сервер;...roles]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| ...roles |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$deleteRoles',
  code: `
$deleteRoles[сервер;...roles]`
// Возвращает: ...
})
```
