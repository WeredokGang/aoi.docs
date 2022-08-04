# $messageURL
desc
### Использование
```php
$messageURL[messageId?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$messageURL',
  code: `
$messageURL[messageId?;канал?]`
// Возвращает: ...
})
```
