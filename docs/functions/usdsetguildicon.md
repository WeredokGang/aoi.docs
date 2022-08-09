# $setGuildIcon
desc
### Использование
```php
$setGuildIcon[avatar;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| avatar |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$setGuildIcon',
  code: `
$setGuildIcon[avatar;сервер?]`
// Возвращает: ...
})
```
