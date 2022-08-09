# $getUserVar
desc
### Использование
```php
$getUserVar[varname;userId?;сервер?;table?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| varname |  |  | Да | 
| userId |  |  | Нет | 
| сервер |  |  | Нет |
| table |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getUserVar',
  code: `
$getUserVar[varname;userId?;сервер?;table?]`
// Возвращает: ...
})
```
