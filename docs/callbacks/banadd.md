# banAdd
Срабатывает при добавлении участника в бан лист сервера
### Использование
```php
bot.onbanAdd()
bot.banAddCommand
```
## Пример(ы)

```javascript
bot.banAddcommand({
  name: 'banAdd',
  code: `
Пользователь $usertag был забанен на сервере $serverName
  $dm[$botownerid]
`
// Возвращает: ...
})
```
