# $isChannelManageable
desc
### Использование
```php
$isChannelManageable[канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$isChannelManageable',
  code: `
$isChannelManageable[канал?]`
// Возвращает: ...
})
```
