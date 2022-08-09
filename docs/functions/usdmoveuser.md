# $moveUser
desc
### Использование
```php
$moveUser[сервер;userId;канал;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| userId |  |  | Да | 
| канал |  |  | Да |
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$moveUser',
  code: `
$moveUser[сервер;userId;канал;reason]`
// Возвращает: ...
})
```
