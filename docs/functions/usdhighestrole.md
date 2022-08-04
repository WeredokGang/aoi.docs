# $highestRole
desc
### Использование
```php
$highestRole[userId?;сервер?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$highestRole',
  code: `
$highestRole[userId?;сервер?;option?]`
// Возвращает: ...
})
```
