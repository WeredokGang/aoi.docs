# $getAttachments
desc
### Использование
```php
$getAttachments[канал;messageId;index?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| messageId |  |  | Да | 
| index |  |  | Нет |
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getAttachments',
  code: `
$getAttachments[канал;messageId;index?;option?]`
// Возвращает: ...
})
```
