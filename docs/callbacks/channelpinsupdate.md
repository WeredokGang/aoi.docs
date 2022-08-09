# channelPinsUpdate
Срабатывает на обновление закрепленных сообщений в канале любого типа: текстовый или ветка
### Использование
```php
bot.onChannelPinsUpdate()
bot.channelPinsUpdateCommand
```
## Пример(ы)

```javascript
bot.channelPinsUpdatecommand({
  name: 'channelPinsUpdate',
  code: `В канале $channelName появилось новое о закрепленные сообщение:
  Автор: $userTag
  Сообщение: $message
`
})
```