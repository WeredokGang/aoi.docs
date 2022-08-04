# $getEmbed
desc
### Использование
```php
$getEmbed[канал?;messageId?;index?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Нет | 
| messageId |  |  | Нет | 
| index |  |  | Нет |
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getEmbed',
  code: `
$getEmbed[канал?;messageId?;index?;option?]`
// Возвращает: ...
})
```
