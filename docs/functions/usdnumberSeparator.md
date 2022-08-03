# $numberSeparator
desc
### Использование
```php
$numberSeparator[number;sep?;']
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| number |  |  | Да | 
| sep |  |  | Нет | 
| ' |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$numberSeparator',
  code: `
$numberSeparator[number;sep?;']`
// Возвращает: ...
})
```