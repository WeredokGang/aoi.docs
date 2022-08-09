# inviteDelete
Срабатывает когда на сервере удаляется ссылка-приглашение
### Использование
```php
bot.onInviteDelete()
bot.inviteDeleteCommand
```
## Пример(ы)

```javascript
bot.inviteDeletecommand({
  name: 'inviteDelete',
  code: `На сервере $serverName была удалена ссылка-приглашение
`
})
```
###### Мало информации