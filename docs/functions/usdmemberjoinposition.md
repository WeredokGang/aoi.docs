# $memberJoinPosition
desc
### Использование
```php
$memberJoinPosition[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$memberJoinPosition',
  code: `
$memberJoinPosition[userId?;сервер?]`
// Возвращает: ...
})
```
