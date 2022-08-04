# $hoistedRole
desc
### Использование
```php
$hoistedRole[userId?;сервер?;option?]
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
  name: '$hoistedRole',
  code: `
$hoistedRole[userId?;сервер?;option?]`
// Возвращает: ...
})
```
