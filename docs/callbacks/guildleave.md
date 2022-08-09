# guildLeave
Срабатывает когда бот покидает сервер
### Использование
```php
bot.onGuildLeave()
bot.guildLeaveCommand
```
## Пример(ы)

```javascript
bot.guildLeavecommand({
  name: 'guildLeave',
  code: ` Я покинул сервер $serverName: $membersCount участников, владелец $userTag[$ownerID]. Приглашение: $createServerInvite
  $dm[$botOwnerID]
`
})
```