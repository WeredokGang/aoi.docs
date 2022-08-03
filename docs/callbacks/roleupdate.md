# roleUpdate
Сообщает об обновлении роли
### Использование
```php
bot.onroleUpdate()
bot.roleUpdateCommand
```
## Пример(ы)

```javascript
bot.roleUpdatecommand({
  name: 'roleUpdate',
  code: `
Роль $oldRole[name] переименована в $newRole[name]
$dm[$botOwnerID]
`
// Возвращает: Роль Deglas Gay переименована в Weredok Legend 
})
```
