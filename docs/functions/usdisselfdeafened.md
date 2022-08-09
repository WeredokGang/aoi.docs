# $isSelfDeafened
desc
### Использование
```php
$isSelfDeafened[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isSelfDeafened',
  code: `
$isSelfDeafened[userId?;сервер?]`
// Возвращает: ...
})
```
