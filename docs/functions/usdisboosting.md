# $isBoosting
desc
### Использование
```php
$isBoosting[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isBoosting',
  code: `
$isBoosting[userId?;сервер?]`
// Возвращает: ...
})
```
