# $messageWebhookId
desc
### Использование
```php
$messageWebhookId[messageId?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$messageWebhookId',
  code: `
$messageWebhookId[messageId?;канал?]`
// Возвращает: ...
})
```
