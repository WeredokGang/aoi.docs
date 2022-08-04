# $memberExists
desc
### Использование
```php
$memberExists[userId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$memberExists',
  code: `
$memberExists[userId;сервер?]`
// Возвращает: ...
})
```
