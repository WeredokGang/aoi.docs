# $channelNSFW
Возвращает логическое выражение если у канала присутствует метка NSFW. Если не указывать айди - выдаст информацию о метке канала, где вызвали функцию
### Использование
```php
$channelNSFW[канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал | канал, данные о метке которого нужно получить | айди | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$channelNSFW',
  code: `
$channelNSFW[9876729376001637]`
// Возвращает: false
})
```
