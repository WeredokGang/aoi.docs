# $membersCount
desc
### Использование
```php
$membersCount[сервер?;presence?;countBot?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| presence |  |  | Нет | 
| countBot |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$membersCount',
  code: `
$membersCount[сервер?;presence?;countBot?]`
// Возвращает: ...
})
```
