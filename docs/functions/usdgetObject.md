# $getObject
desc
### Использование
```php
$getObject[format?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| format |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$getObject',
  code: `
$getObject[format?]`
// Возвращает: ...
})
```