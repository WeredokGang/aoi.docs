# $timeoutMember
desc
### Использование
```php
$timeoutMember[сервер?;memberId?;timeout?;timeoutEndsAt?;reason;]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| memberId |  |  | Нет | 
| timeout |  |  | Нет |
| timeoutEndsAt |  |  | Нет |
| reason |  |  | Да |
|  |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$timeoutMember',
  code: `
$timeoutMember[сервер?;memberId?;timeout?;timeoutEndsAt?;reason;]`
// Возвращает: ...
})
```
