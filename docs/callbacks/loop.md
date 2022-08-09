# loop
Выполняет один и тот же код постоянно с указанной задержкой
### Использование
```php
bot.loopCommand
```
## Пример(ы)

```javascript
bot.loopCommand({
  name: 'loop',
  executeOnStartUp: true / false, //Начинать ли выполнение после старта борта
  every: мс, //Количество миллисекунд для задержки
  code: `$log[Привет!]
`

})
```