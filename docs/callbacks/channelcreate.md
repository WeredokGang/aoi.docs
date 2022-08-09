# channelCreate
Срабатывает на создание канала на сервере любого типа: текстовый, голосовой, категория, трибуна или ветка. Для получения свойств канала используйте функции [$newChannel](functions/usdnewchannel.md) и [$oldChannel](functions/usdoldchannel.md)
### Использование
```php
bot.onChannelCreate()
bot.channelCreateCommand
```
## Пример(ы)

```javascript
bot.channelCreatecommand({
  name: 'channelCreate',
  code: `На сервере $servername был создан канал $newchannel[name]
  $dm[$botownerid]
`
})
```