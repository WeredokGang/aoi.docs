# $getMessageVar
desc
### Использование
```php
$getMessageVar[varname;сообщение?;table?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| varname |  |  | Да | 
| сообщение |  |  | Нет | 
| table |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getMessageVar',
  code: `
$getMessageVar[varname;сообщение?;table?]`
// Возвращает: ...
})
```
