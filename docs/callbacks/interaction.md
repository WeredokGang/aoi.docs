# interaction
Нужен для создания интерактивных взаимодействий. Чтобы не было ошибки нужно использовать функцию [$interactionReply](function/usdinteractionreply)
### Использование
```php
bot.onInteractionCreate()
bot.interactionCommand
```
## Пример(ы)

```javascript
bot.command({
  name: "Привет",
  code: `Нажми на кнопку!
  $addButton[1;Привет;1;interaction]`
})
bot.interactionCommand({
  name: 'interaction',
prototype: "прототип", //button, selectMenu, modal, slash, autoComplete
  code: `$interactionReplу[Привет!]
`
})
```