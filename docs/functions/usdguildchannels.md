# $guildChannels
desc
### Использование
```php
$guildChannels[сервер?;option?;sep?;']
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| option |  |  | Нет | 
| sep |  |  | Нет |
| ' |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$guildChannels',
  code: `
$guildChannels[сервер?;option?;sep?;']`
// Возвращает: ...
})
```
