# $reactionCollector
desc
### Использование
```php
$reactionCollector[канал;сообщение;userFilters;time;reactions;awaits;removeReaction?;awaitData?;endAwait;]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| сообщение |  |  | Да | 
| userFilters |  |  | Да |
| time |  |  | Да |
| reactions |  |  | Да |
| awaits |  |  | Да |
| removeReaction |  |  | Нет |
| awaitData |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$reactionCollector',
  code: `
$reactionCollector[канал;сообщение;userFilters;time;reactions;awaits;removeReaction?;awaitData?;endAwait;]`
// Возвращает: ...
})
```
