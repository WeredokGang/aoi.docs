# $hasAnyRole
desc
### Использование
```php
$hasAnyRole[сервер;userId;...roles]
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
  name: '$hasAnyRole',
  code: `
$hasAnyRole[сервер;userId;...roles]`
// Возвращает: ...
})
```
