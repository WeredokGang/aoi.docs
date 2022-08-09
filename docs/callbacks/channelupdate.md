# channelUpdate
Срабатывает на обновление канала на сервере любого типа: текстовый, голосовой, категория, трибуна или ветка. Для получения свойств канала используйте функции [$newChannel](functions/usdnewchannel.md) и [$oldChannel](functions/usdoldchannel.md)
### Использование
```php
bot.onChannelUpdate()
bot.channelUpdateCommand
```
## Пример(ы)

```javascript
bot.channelUpdatecommand({
  name: 'channelUpdate',
  code: `На сервере $serverName был обновлён канал $newChannel[name]
`
})
```