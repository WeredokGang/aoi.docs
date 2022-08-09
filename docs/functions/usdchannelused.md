# $channelUsed
Возвращает канал где был вызван обратный вызов. Используется для обратных вызовов [messageUpdate](callbacks/messageupdate) и [messageDelete](callbacks/messagedelete)
### Использование
```php
$channelUsed
```

## Пример(ы)

```javascript
bot.messageUpdateCommand({
  name: '$channelUsed',
  code: `
$channelUsed`
// Возвращает: 9976792826680276
})
```
