# $getServerVar
desc
### Использование
```php
$getServerVar[varname;сервер?;table?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| varname |  |  | Да | 
| сервер |  |  | Нет | 
| table |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getServerVar',
  code: `
$getServerVar[varname;сервер?;table?]`
// Возвращает: ...
})
```
