# $editChannel
Изменяет канал
### Использование
```php
$editChannel[канал;...fields]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| ...fields |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$editChannel',
  code: `
$editChannel[канал;...fields]`
// Возвращает: ...
})
```
