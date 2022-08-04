# $isSelfMuted
desc
### Использование
```php
$isSelfMuted[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isSelfMuted',
  code: `
$isSelfMuted[userId?;сервер?]`
// Возвращает: ...
})
```
