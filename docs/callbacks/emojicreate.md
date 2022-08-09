# emojiCreate
Срабатывает когда на сервере создаётся эмоджи любого типа: анимированные или обычные 
### Использование
```php
bot.onEmojiCreate()
bot.emojiCreateCommand
```
## Пример(ы)

```javascript
bot.emojiCreatecommand({
  name: 'emojiCreate',
  code: `На сервере $serverName был создан новый эмоджи
`
})
```
###### Мало информации