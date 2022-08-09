# roleDelete
Сообщает об удалении роли
### Использование
```php
bot.onroleDelete()
bot.roleDeleteCommand
```
## Пример(ы)

```javascript
bot.roleDeletecommand({
  name: 'roleDelete',
  code: `Была удалена роль: $oldRole[name]
$dm[$botOwnerID]
`
// Возвращает: Была удалена роль: Deglas Gay
})
```
