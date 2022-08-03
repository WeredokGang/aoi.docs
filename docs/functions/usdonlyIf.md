# $onlyIf
desc
### Использование
```php
$onlyIf[condition;err?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| condition |  |  | Да | 
| err |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$onlyIf',
  code: `
$onlyIf[condition;err?]`
// Возвращает: ...
})
```