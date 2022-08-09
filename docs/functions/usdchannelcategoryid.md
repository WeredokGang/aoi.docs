# $channelCategoryID

### Использование
```php
$channelCategoryID[channelID?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| channelID |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$channelCategoryID',
  code: `
$channelCategoryID[channelID?]`
// Возвращает: ...
})
```