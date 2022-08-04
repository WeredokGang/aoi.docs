# $memberAvatar
desc
### Использование
```php
$memberAvatar[сервер?;userId?;size?;dynamic?;format;]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| userId |  |  | Нет | 
| size |  |  | Нет |
| dynamic |  |  | Нет |
| format |  |  | Да |
|  |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$memberAvatar',
  code: `
$memberAvatar[сервер?;userId?;size?;dynamic?;format;]`
// Возвращает: ...
})
```
