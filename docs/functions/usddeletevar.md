# $deleteVar
desc
### Использование
```php
$deleteVar[variable;id;table?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| variable |  |  | Да | 
| id |  |  | Да | 
| table |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$deleteVar',
  code: `
$deleteVar[variable;id;table?]`
// Возвращает: ...
})
```
