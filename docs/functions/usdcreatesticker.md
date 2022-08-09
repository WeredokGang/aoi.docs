# $createSticker
desc
### Использование
```php
$createSticker[guildid;url;name;returnSticker?;tags;description;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| guildid |  |  | Да | 
| url |  |  | Да | 
| name |  |  | Да |
| returnSticker |  |  | Нет |
| tags |  |  | Да |
| description |  |  | Да |
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$createSticker',
  code: `
$createSticker[guildid;url;name;returnSticker?;tags;description;reason]`
// Возвращает: ...
})
```
