# ready
Сообщает о том что бот включился 
### Использование
```php
bot.onready()
bot.readyCommand
```
## Пример(ы)

```javascript
bot.readycommand({
  name: 'ready',
  code: `
$log[$usertag[$clientid] включился!]
`
// Возвращает: Bugcat#5945 включился!
})
```
