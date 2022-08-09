# $isMentionable
desc
### Использование
```php
$isMentionable[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isMentionable',
  code: `
$isMentionable[roleId;сервер?]`
// Возвращает: ...
})
```
