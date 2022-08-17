# $disableMentionType
Отключает упоминания определённого типа в сообщении бота о
### Использование
```php
$disableMentionType[тип?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| тип | тип упоминания (user, role, channel, everyone) | текст | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$disableMentionType',
  code: ` @everyone
$disableMentionType[everyone]`
// Возвращает: @everyone
})
```
