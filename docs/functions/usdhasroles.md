# $hasRoles
desc
### Использование
```php
$hasRoles[сервер;userId;...roles]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| userId |  |  | Да | 
| ...roles |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$hasRoles',
  code: `
$hasRoles[сервер;userId;...roles]`
// Возвращает: ...
})
```
