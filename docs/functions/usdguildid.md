# $guildID
desc
### Использование
```php
$guildID[name?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| name |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$guildID',
  code: `
$guildID[name?]`
// Возвращает: ...
})
```
