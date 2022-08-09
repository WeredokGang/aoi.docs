# memberUpdate
Срабатывает когда участник обновляет свой профиль на сервере: никнейм, баннер, аватар или роли
### Использование
```php
bot.onМemberUpdate()
bot.memberUpdateCommand
```
## Пример(ы)

```javascript
bot.memberUpdatecommand({
  name: 'memberUpdate',
  code: `На сервере $serverName участник $username обновил свой профиль
  $dm[$botOwnerId]
`
})
```