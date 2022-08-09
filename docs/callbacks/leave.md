# leave
Срабатывает когда кто-либо выходит с сервера
### Использование
```php
bot.onLeave()
bot.leaveCommand
```
## Пример(ы)

```javascript
bot.leavecommand({
  name: 'leave',
  code: `Пользователь $userTag покинул сервер $serverName
  $dm[$botOwnerID]
`
})
```