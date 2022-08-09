# banRemove
Срабатывает когда разравнивается человек на сервере
### Использование
```php
bot.onBanRemove()
bot.banRemoveCommand
```
## Пример(ы)

```javascript
bot.banRemovecommand({
  name: 'banRemove',
  code: `Пользователь $usertag был разбанен на сервере $serverName
  $dm[$botownerid]
`

})
```