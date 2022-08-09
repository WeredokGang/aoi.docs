# $deleteChannels
Удаляет указанные каналы
### Использование
```php
$deleteChannels[...каналы]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| ...каналы | каналы, которые нужно удалить | перечисление | Да |  
## Пример(ы)

```javascript
bot.command({
  name: '$deleteChannels',
  code: `
$deleteChannels[$mentionedChannels[1];$mentionedChannels[2];$mentionedChannels[3]]`
})
```
