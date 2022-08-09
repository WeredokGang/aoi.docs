# $resetUserVar
desc
### Использование
```php
$resetUserVar[varname;сервер?;table?]
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
  name: '$resetUserVar',
  code: `
$resetUserVar[varname;сервер?;table?]`
// Возвращает: ...
})
```
