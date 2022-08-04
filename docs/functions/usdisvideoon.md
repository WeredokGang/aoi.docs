# $isVideoOn
desc
### Использование
```php
$isVideoOn[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isVideoOn',
  code: `
$isVideoOn[userId?;сервер?]`
// Возвращает: ...
})
```
