# $getAttachments
desc
### Использование
```php
$getAttachments[канал;сообщение;index?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| сообщение |  |  | Да | 
| index |  |  | Нет |
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getAttachments',
  code: `
$getAttachments[канал;сообщение;index?;option?]`
// Возвращает: ...
})
```
