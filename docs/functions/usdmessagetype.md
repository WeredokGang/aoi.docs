# $messageType
desc
### Использование
```php
$messageType[messageId?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$messageType',
  code: `
$messageType[messageId?;канал?]`
// Возвращает: ...
})
```
