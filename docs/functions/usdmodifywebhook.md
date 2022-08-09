# $modifyWebhook
desc
### Использование
```php
$modifyWebhook[webhookId;name;avatar;канал?;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| webhookId |  |  | Да | 
| name |  |  | Да | 
| avatar |  |  | Да |
| канал |  |  | Нет |
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$modifyWebhook',
  code: `
$modifyWebhook[webhookId;name;avatar;канал?;reason]`
// Возвращает: ...
})
```
