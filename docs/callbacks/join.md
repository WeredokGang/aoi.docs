# join
Срабатывает когда кто-либо присоединяется к серверу
### Использование
```php
bot.onJoin()
bot.joinCommand
```
## Пример(ы)

```javascript
bot.joincommand({
  name: 'join',
  code: `На сервер $serverName присоединился новый участник: $userTag ($authorID)
`
})
```