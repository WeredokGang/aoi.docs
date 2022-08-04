# applicationCmdUpdate
Срабатывает когда обновляется аппликация (слэш-команда)
### Использование
```php
bot.onАpplicationCmdUpdate()
bot.applicationCmdUpdateCommand
```
## Пример(ы)

```javascript
bot.applicationCmdUpdatecommand({
  name: 'applicationCmdUpdate',
  code: `$sendDm[Была создана новая слэш-команда на сервере $serverName ($guildID);$botownerid]
`
// Возвращает: ...
})
```
