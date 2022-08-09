# guildUpdate
Срабатывает когда обновляется сервер: иконка, название, описание или настройки
### Использование
```php
bot.onGuildUpdate()
bot.guildUpdateCommand
```
## Пример(ы)

```javascript
bot.guildUpdatecommand({
  name: 'guildUpdate',
  code: `Сервер $serverName был обновлён
  $dm[$botOwnerID]
`
})
```