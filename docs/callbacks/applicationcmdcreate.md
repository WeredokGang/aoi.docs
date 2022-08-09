# applicationCmdCreate
Срабатывает когда создаётся аппликация (слэш-команда)
### Использование
```php
bot.onАpplicationCmdCreate()
bot.applicationCmdCreateCommand
```
## Пример(ы)

```javascript
bot.applicationCmdCreatecommand({
  name: 'applicationCmdCreate',
  code: `$sendDm[Была создана новая слэш-команда на сервере $serverName ($guildID);$botownerid]
`
})
```
