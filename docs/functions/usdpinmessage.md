# $pinMessage
desc
### Использование
```php
$pinMessage[messageId?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$pinMessage',
  code: `
$pinMessage[messageId?;канал?]`
// Возвращает: ...
})
```
