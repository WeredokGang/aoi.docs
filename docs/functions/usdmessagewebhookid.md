# $messageWebhookId
desc
### Использование
```php
$messageWebhookId[сообщение?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сообщение |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$messageWebhookId',
  code: `
$messageWebhookId[сообщение?;канал?]`
// Возвращает: ...
})
```
