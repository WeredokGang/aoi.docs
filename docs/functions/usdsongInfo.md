# $songInfo
desc
### Использование
```php
$songInfo[response?;position?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| response |  |  | Нет | 
| position |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$songInfo',
  code: `
$songInfo[response?;position?]`
// Возвращает: ...
})
```