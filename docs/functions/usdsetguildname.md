# $setGuildName
desc
### Использование
```php
$setGuildName[name;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| name |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$setGuildName',
  code: `
$setGuildName[name;сервер?]`
// Возвращает: ...
})
```
