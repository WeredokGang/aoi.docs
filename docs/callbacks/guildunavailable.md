# guildUnavailable
Срабатывает когда сервер становится недоступным. Например его удалили, или он недоступен из-за временных работ Discord на сервере
### Использование
```php
bot.onGuildUnavailable()
bot.guildUnavailableCommand
```
## Пример(ы)

```javascript
bot.guildUnavailablecommand({
  name: 'guildUnavailable',
  code: `Сервер $serverName больше недоступен
  $dm[$botownerid]
`
})
```