# $editGuild
desc
### Использование
```php
$editGuild[сервер;...guildDatas]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| ...guildDatas |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$editGuild',
  code: `
$editGuild[сервер;...guildDatas]`
// Возвращает: ...
})
```
