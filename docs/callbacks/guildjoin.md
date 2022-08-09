# guildJoin
Срабатывает когда бот присоединяется к серверу
### Использование
```php
bot.onGuildJoin()
bot.guildJoinCommand
```
## Пример(ы)

```javascript
bot.guildJoincommand({
  name: 'guildJoin',
  code: `Я присоединился к серверу $serverName: $membersCount участников, владелец $userTag[$ownerID]. Приглашение: $createServerInvite
  $dm[$botOwnerID]
`
})
```