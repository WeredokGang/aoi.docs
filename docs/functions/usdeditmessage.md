# $editMessage
desc
### Использование
```php
$editMessage[messageId;msg;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Да | 
| msg |  |  | Да | 
| канал |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$editMessage',
  code: `
$editMessage[messageId;msg;канал?]`
// Возвращает: ...
})
```
