# $getMessage
desc
### Использование
```php
$getMessage[канал?;messageId?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Нет | 
| messageId |  |  | Нет | 
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$getMessage',
  code: `
$getMessage[канал?;messageId?;option?]`
// Возвращает: ...
})
```
