# $highestGuildRole
desc
### Использование
```php
$highestGuildRole[сервер?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| option |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$highestGuildRole',
  code: `
$highestGuildRole[сервер?;option?]`
// Возвращает: ...
})
```
