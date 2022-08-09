# channelDelete
Срабатывает на удаление канала на сервере любого типа: текстовый, голосовой, категория, трибуна или ветка. Для получения свойств канала используйте функции [$newChannel](functions/usdnewchannel.md) и [$oldChannel](functions/usdoldchannel.md)

### Использование
```php
bot.onchannelDelete()
bot.channelDeleteCommand
```
## Пример(ы)

```javascript
bot.channelDeletecommand({
  name: 'channelDelete',
  code: `На сервере $serverName был удалён канал $oldChannel[name]
  $dm[$botOwnerid]
`

})
```