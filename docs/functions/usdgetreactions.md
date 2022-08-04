# $getReactions
desc
### Использование
```php
$getReactions[канал;messageId;reaction;force?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| messageId |  |  | Да | 
| reaction |  |  | Да |
| force |  |  | Нет |
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getReactions',
  code: `
$getReactions[канал;messageId;reaction;force?;option?]`
// Возвращает: ...
})
```
