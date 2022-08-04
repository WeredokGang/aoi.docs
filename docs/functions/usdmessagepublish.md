# $messagePublish
desc
### Использование
```php
$messagePublish[messageId?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$messagePublish',
  code: `
$messagePublish[messageId?;канал?]`
// Возвращает: ...
})
```
