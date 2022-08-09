# presenceUpdate
Сообщает об обновлении статуса пользователя 
### Использование
```php
bot.onpresenceUpdate()
bot.presenceUpdateCommand
```
## Пример(ы)

```javascript
bot.presenceUpdatecommand({
  name: 'presenceUpdate',
  code: `
$username обновил статус!
Старый статус:  $oldPresence[status]
$dm[$botOwnerID]
`
// Возвращает: ! Big Boy Deglas обновил статус!
// Старый статус: С большой силой приходит большая ответственность
})
```
