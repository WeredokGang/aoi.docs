# $isServerDeafened
desc
### Использование
```php
$isServerDeafened[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isServerDeafened',
  code: `
$isServerDeafened[userId?;сервер?]`
// Возвращает: ...
})
```
