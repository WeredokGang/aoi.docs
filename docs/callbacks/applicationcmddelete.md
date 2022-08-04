# applicationCmdDelete
Срабатывает когда удаляется аппликация (слэш-команда)
### Использование
```php
bot.onАpplicationCmdDelete()
bot.applicationCmdDeleteCommand
```
## Пример(ы)

```javascript
bot.applicationCmdDeletecommand({
  name: 'applicationCmdDelete',
  code: `$sendDm[Была удалена слэш-команда на сервере $serverName ($guildID);$botownerid]
`
})
```
