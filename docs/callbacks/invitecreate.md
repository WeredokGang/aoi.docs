# inviteCreate
Срабатывает когда на сервере создаётся ссылка-приглашение
### Использование
```php
bot.onInviteCreate()
bot.inviteCreateCommand
```
## Пример(ы)

```javascript
bot.inviteCreatecommand({
  name: 'inviteCreate',
  code: `На сервере $serverName была создана ссылка-приглашение
`
})
```
###### Мало информации