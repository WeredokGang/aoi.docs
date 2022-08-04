# $messageFlags
desc
### Использование
```php
$messageFlags[messageId;sep?;';канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Да | 
| sep |  |  | Нет | 
| ' |  |  | Да |
| канал |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$messageFlags',
  code: `
$messageFlags[messageId;sep?;';канал?]`
// Возвращает: ...
})
```
