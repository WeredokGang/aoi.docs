# $playTrack
desc
### Использование
```php
$playTrack[type;track]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| type |  |  | Да | 
| track |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$playTrack',
  code: `
$playTrack[type;track]`
// Возвращает: ...
})
```