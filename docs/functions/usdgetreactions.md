# $getReactions
desc
### Использование
```php
$getReactions[канал;сообщение;reaction;force?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| сообщение |  |  | Да | 
| reaction |  |  | Да |
| force |  |  | Нет |
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getReactions',
  code: `
$getReactions[канал;сообщение;reaction;force?;option?]`
// Возвращает: ...
})
```
