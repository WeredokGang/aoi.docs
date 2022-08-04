# $messageExists
desc
### Использование
```php
$messageExists[messageId;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Да | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$messageExists',
  code: `
$messageExists[messageId;канал?]`
// Возвращает: ...
})
```
