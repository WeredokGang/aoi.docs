# $deleteChannel
Удаляет указанный канал
### Использование
```php
$deleteChannel[канал]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал | канал, который нужно удалить | айди | Да |  
## Пример(ы)

```javascript
bot.command({
  name: '$deleteChannel',
  code: `
$deleteChannel[$mentionedChannels]`
})
```
