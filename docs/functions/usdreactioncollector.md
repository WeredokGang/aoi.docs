# $reactionCollector
desc
### Использование
```php
$reactionCollector[канал;messageId;userFilters;time;reactions;awaits;removeReaction?;awaitData?;endAwait;]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| messageId |  |  | Да | 
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
$reactionCollector[канал;messageId;userFilters;time;reactions;awaits;removeReaction?;awaitData?;endAwait;]`
// Возвращает: ...
})
```
